# TimeSync - Sistema de Gestão de Tempo para Freelancers e Trabalhadores Remotos

**TimeSync** é uma aplicação web desenvolvida para ajudar freelancers, trabalhadores remotos e equipes distribuídas a gerenciar seu tempo de maneira eficiente. A aplicação oferece recursos de agendamento, monitoramento de produtividade e geração de relatórios para melhorar a gestão do tempo e a produtividade.

---

## Funcionalidades

- **Cadastro e Login de Usuários**: Permite o cadastro de usuários com autenticação JWT.
- **Dashboard Pessoal**: Visão geral das tarefas programadas, tempo gasto e progresso das metas.
- **Gestão de Tarefas**: Criar, editar e excluir tarefas com prazos e categorias.
- **Rastreamento de Tempo em Tempo Real**: Um timer para registrar o tempo dedicado a cada tarefa.
- **Relatórios Detalhados**: Geração de relatórios semanais e mensais sobre o tempo dedicado às tarefas.
- **Metas de Produtividade**: Defina metas mensais ou semanais de produtividade.
- **Integração com Calendário**: Sincronize seus compromissos com Google Calendar ou Outlook.
- **Modo Pomodoro**: Utilize o método Pomodoro para melhorar a produtividade.
- **Notificações**: Lembretes de tarefas e alertas para atingir metas.

## Tecnologias Utilizadas

### Front-End:
- **React.js**: Para criar a interface do usuário interativa e dinâmica.
- **TailwindCSS**: Para criar um design responsivo e elegante de maneira rápida.

### Back-End:
- **Spring Boot (Java)**: Para criar a API RESTful.
- **PostgreSQL (Neon.tech)**: Banco de dados relacional para armazenar usuários, tarefas, metas e relatórios.
- **JWT (JSON Web Token)**: Para autenticação e gerenciamento de sessões de usuários.

### Extras:
- **Docker**: Em andamento...
- **WebSockets**: Para comunicação em tempo real (exemplo: timer que atualiza em tempo real).
  
---

## Como Rodar o Projeto Localmente

### Pré-requisitos

- **Java** instalado (versão 17.x ou superior).
- **Node** instalado
- **Docker** (opcional, para rodar com containers).

### 1. Clonar o repositório

```bash
git clone https://github.com/fernandomp26/time-sync.git
cd time-sync
