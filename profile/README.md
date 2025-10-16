# 🏋️‍♂️ Equilíbrio – App da Academia Tapera

<img width="500" height="500" alt="logo" src="https://github.com/user-attachments/assets/b8c494b0-5b58-4f8e-bb67-5f57ecf6cdc5" />

## 🧭 Visão Geral

O **Equilíbrio App** é o sistema oficial da academia **Equilíbrio**, localizada na **Tapera (Florianópolis/SC)**.  
O objetivo do aplicativo é oferecer uma experiência moderna, conectada e eficiente para alunos e instrutores.

Através do app, o aluno pode acompanhar seu progresso, acessar treinos personalizados, agendar aulas e monitorar sua evolução física.  
Já os instrutores podem gerenciar planos, horários e avaliações de forma centralizada, garantindo mais praticidade e organização no dia a dia da academia.

---

## ⚙️ Funcionalidades Principais

### 👤 Para Alunos
- **Cadastro e login seguros** com autenticação simples via Supabase.  
- **Visualização de treinos personalizados**, com descrição de exercícios, vídeos e séries.  
- **Acompanhamento de progresso físico**, com gráficos de evolução de peso, massa magra e medidas.  
- **Agendamento de aulas** e controle de presença.  
- **Notificações** e lembretes sobre treinos e mensagens dos instrutores.  
- **Integração com o Supabase Storage** para upload de fotos e vídeos de progresso.

### 🏋️‍♂️ Para Instrutores
- **Criação e personalização de treinos** para cada aluno.  
- **Avaliação física digital** e armazenamento seguro dos dados no banco Supabase.  
- **Gestão de agenda e alunos**, com visualização de horários e treinos ativos.  
- **Envio de mensagens e alertas personalizados** para cada aluno.

### 💼 Para Administração
- **Gerenciamento de usuários (alunos e instrutores)** dentro do painel administrativo.  
- **Controle de planos e treinos**.  
- **Sistema de notificações internas.**

---

## 💡 Como Funciona

1. O aluno baixa o aplicativo **Equilíbrio** (Android e iOS).  
2. Faz o cadastro e é vinculado a um instrutor.  
3. O instrutor cria um treino personalizado no painel interno.  
4. O aluno recebe os treinos, executa e registra seu progresso.  
5. Todos os dados são salvos e sincronizados automaticamente via **Supabase**.  

---

## 🧱 Requisitos Funcionais

| Nº | Requisito | Descrição |
|----|------------|-----------|
| RF01 | Cadastro de usuários | Permitir o registro de alunos, instrutores e administradores. |
| RF02 | Login e autenticação | Sistema simples com Supabase Auth. |
| RF03 | Gerenciamento de treinos | Criar, editar e excluir planos personalizados. |
| RF04 | Acompanhamento de progresso | Exibir evolução física e estatísticas. |
| RF05 | Sistema de agendamento | Permitir marcação e cancelamento de aulas. |
| RF06 | Notificações | Enviar alertas de treino e mensagens. |
| RF07 | Gestão administrativa | Administrar usuários, treinos e planos. |
| RF08 | Armazenamento de mídia | Upload de fotos e vídeos via Supabase Storage ou AWS S3. |
| RF09 | Segurança e backup | Garantir integridade e disponibilidade dos dados. |

---

## 🧰 Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-------------|
| **App Mobile** | Expo – React Native |
| **Banco de Dados** | PostgreSQL com Supabase |
| **Autenticação** | Supabase Auth (cadastro simples) |
| **Notificações Push** | Implementação nativa (sem FCM) |
| **Interface** | Separada para cliente e administrador (dentro do app) |
| **Armazenamento de mídia** | AWS S3 / Supabase Storage |

---

## 🏗️ Estrutura da Organização no GitHub

Organização: [**development-in-react-native**](https://github.com/development-in-react-native)

```

development-in-react-native/  
├── equilibrio-app/ # Aplicativo mobile (Expo / React Native)  
├── equilibrio-api/ # Backend (Node.js + Supabase)  
├── equilibrio-design-system/ # Componentes compartilhados (UI)  
└── equilibrio-docs/ # Documentação e guias técnicos

```

Cada repositório possui seu próprio `README.md` com instruções de instalação, configuração e contribuição.

---

## 🧑‍💻 Contribuição

Quer contribuir com o projeto?

1. Faça um **fork** do repositório.  
2. Crie uma nova **branch**:

   ```bash
   git checkout -b feature/nova-funcionalidade
   ```

4. Faça o **commit** das suas alterações:

    ```bash
    git commit -m "Adiciona nova funcionalidade"
    ```
    
5. Envie para o repositório remoto:

    ```bash
    git push origin feature/nova-funcionalidade
    ```
    
6. Abra um **Pull Request** para revisão.
    

* * *

## 🔒 Licença

O projeto é distribuído sob a licença **MIT**, permitindo uso e modificação livre, desde que atribuída a autoria original.

* * *

## 📞 Contato

📱 **WhatsApp:** [Clique aqui para conversar](https://l.instagram.com/?u=https%3A%2F%2Fapi.whatsapp.com%2Fsend%3Fphone%3D48992191129%26fbclid%3DPAZXh0bgNhZW0CMTEAAaebgfVDfgT4TonVp9Nz7LjH8ijapEJa-N3Lf5YZXgIvsTAPCdU7yyzdVw-YrQ_aem_DHEiyglJ_8MkDyvOFePgUA&e=AT1aRrWP9jivlHb-iU9UVfCaySLmMfgpsAibFTAb-NaIucHOcep9eIfoGYHtJFSidCNODP5rDgC_Ak5CEnO8NayGIfaRJXlyNExXynx3lQ)  
📸 **Instagram:** [@academiaequilibriofloripa](https://www.instagram.com/academiaequilibriofloripa/?hl=en)

* * *
