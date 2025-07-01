# 🛒 Digital Store - Backend

API completa para e-commerce desenvolvida com **Node.js**, **Express**, **Sequelize** e **PostgreSQL**.

---

## ✅ Pré-requisitos

Certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- [Git](https://git-scm.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Visual Studio Code](https://code.visualstudio.com/)

---

## 🚀 Como rodar o projeto localmente

1. **Clone o repositório**

```bash
git clone https://github.com/JLS-X/digtal-store.git
cd digtal-store
Instale as dependências

npm install
Configure as variáveis de ambiente

Crie um arquivo .env na raiz do projeto e adicione:

DB_HOST=localhost
DB_PORT=5432
DB_USER=seu_usuario
DB_PASSWORD=sua_senha
DB_NAME=nome_do_banco
JWT_SECRET=sua_chave_secreta
Obs: Altere os valores conforme seu ambiente PostgreSQL.

Execute as migrations (caso use Sequelize CLI)

Se o projeto utilizar migrations via Sequelize CLI, adicione esse passo. Caso contrário, ignore.

npx sequelize db:migrate
Inicie o servidor em modo desenvolvimento

npm run dev
O servidor estará disponível em:
👉 http://localhost:3001

🧪 Rodando os testes
Para rodar os testes automatizados:

npm test

📦 Scripts disponíveis
Comando	Descrição
npm start	Inicia o servidor em modo produção
npm run dev	Inicia o servidor com nodemon
npm test	Executa os testes com jest e supertest

🧰 Tecnologias utilizadas
Node.js

Express

Sequelize

PostgreSQL

JWT

bcryptjs

dotenv

Jest + Supertest

📂 Estrutura básica

digital-store/
├── src/
│   ├── server.js
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── config/
├── .env
├── package.json
└── README.md
.
