Gerenciador de Tarefas Fullstack

Uma aplicação web **Fullstack** para gerenciamento de tarefas diárias (To-Do List), desenvolvida com **Node.js**, **Express**, **PostgreSQL** e **JavaScript Vanilla**, com deploy ativo na nuvem via **Render**.

---

## 🌐 Demo Online

Acesse o projeto publicado: https://gerenciador-tarefas-iehs.onrender.com/

---

## 🚀 Funcionalidades

- **CRUD Completo de Tarefas:**
  - **Create:** Adição de novas tarefas.
  - **Read:** Listagem de tarefas cadastradas.
  - **Update:** Marcação/desmarcação de status de conclusão da tarefa.
  - **Delete:** Remoção de tarefas do banco de dados.
- **Persistência de Dados:** Integração com banco de dados relacional PostgreSQL na nuvem.
- **API RESTful:** Comunicação assíncrona cliente-servidor via requisições HTTP (`fetch`).
- **Interface Responsiva:** Visual simples e intuitivo para uso em dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

### **Back-end**
- **Node.js:** Ambiente de execução JavaScript no servidor.
- **Express:** Framework web para construção da API REST e atendimento a arquivos estáticos.
- **PostgreSQL (`pg`):** Banco de dados relacional gerenciado na nuvem.
- **CORS:** Middleware para controle de acesso às rotas da API.

### **Front-end**
- **HTML5:** Estruturação semântica.
- **CSS3:** Estilização e layout responsivo.
- **JavaScript (ES6+):** Consumo da API via `async/await` e manipulação dinâmica do DOM.

### **Infraestrutura / Deploy**
- **Render:** Hospedagem do Web Service (Node.js) e do banco de dados PostgreSQL.
- **Git & GitHub:** Versionamento de código e deploy automatizado.

---

## 📂 Estrutura do Projeto

```text
gerenciador-tarefas/
├── public/
│   ├── index.html      # Interface principal
│   └── app.js          # Consumo da API e manipulação do DOM
├── server.js           # Servidor Express, rotas da API e conexão DB
├── package.json        # Dependências e scripts do projeto
└── README.md           # Documentação do repositório
🔧 Como Executar Localmente
Pré-requisitos
Node.js instalado na sua máquina.

Instância local ou remota de banco de dados (PostgreSQL ou SQLite).

Passo a Passo
Clone o repositório:

Bash
git clone [https://github.com/diegok29/gerenciador-tarefas.git](https://github.com/diegok29/gerenciador-tarefas.git)
Acesse a pasta do projeto:

Bash
cd gerenciador-tarefas
Instale as dependências:

Bash
npm install
Configure a variável de ambiente:
Crie um arquivo .env na raiz do projeto contendo a string de conexão do seu banco de dados:

Snippet de código
DATABASE_URL=postgres://usuario:senha@localhost:5432/nome_do_banco
Inicie o servidor:

Bash
node server.js
Acesse no navegador:

Plaintext
http://localhost:3000
👤 Autor
Desenvolvido por Diego

GitHub: @diegok29

Projeto desenvolvido para consolidação de arquitetura Fullstack, APIs RESTful e integração com banco de dados na nuvem
