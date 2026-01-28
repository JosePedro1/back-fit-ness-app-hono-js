# Fitness App Backend

Este é o backend para o aplicativo Fitness App, desenvolvido para gerenciar rotinas de exercícios, dietas e acompanhar o progresso físico dos usuários. A aplicação utiliza o framework Hono.js, focado em alta performance e baixa latência.

## Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias e bibliotecas:

* **Hono.js**: Framework web de alta performance.
* **Supabase**: Banco de dados e autenticação baseada em PostgreSQL.
* **JSON Web Token (JWT)**: Implementação de segurança para autenticação de rotas.
* **Bcrypt.js**: Criptografia de senhas para armazenamento seguro.
* **Node-cron**: Agendamento de tarefas automáticas no servidor.
* **Nodemailer**: Serviço de envio de e-mails transacionais.
* **Dotenv**: Gerenciamento de variáveis de ambiente.

## Funcionalidades

* Autenticação de usuários com criptografia de ponta a ponta.
* CRUD completo para gestão de treinos e rotinas alimentares.
* Sistema de monitoramento de métricas físicas e progresso.
* Automação de tarefas e notificações via cron jobs.
* Integração com serviço de e-mail para suporte ao usuário.

## Configuração do Projeto

### Pré-requisitos
* Node.js v18 ou superior.
* Instância ativa no Supabase.

### Instalação

1. Clone o repositório:
   ```bash
   git clone [https://github.com/JosePedro1/back-fit-ness-app-hono-js.git](https://github.com/JosePedro1/back-fit-ness-app-hono-js.git)
   cd back-fit-ness-app-hono-js
