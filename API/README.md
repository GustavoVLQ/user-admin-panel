# user-admin-panel

Aplicação fullstack para gerenciamento de usuários, com funcionalidades de cadastro e exclusão.  
Frontend desenvolvido com **React** e backend com **Node.js + Express**, utilizando **Prisma** como ORM e **MongoDB Atlas** como banco de dados.

## 🔧 Tecnologias Utilizadas

- ⚙️ Backend: Node.js + Express  
- 🧠 Banco de Dados: MongoDB Atlas  
- 🔌 ORM: Prisma  
- 💻 Frontend: React + Vite  
- 🧪 API RESTful  

## 📁 Estrutura do Projeto

```
📦 user-management/
├── backend/         # API com Express + Prisma + MongoDB
└── frontend/        # Interface React conectada à API
```

## 🚀 Como rodar localmente

### 1. Clone o repositório

```bash
git clone https://github.com/GustavoVLQ/user-management.git
cd user-management
```

### 2. Inicie o backend

```bash
cd backend
npm install
```

Crie um arquivo `.env` com:

```
DATABASE_URL="mongodb+srv://seu_usuario:senha@cluster.mongodb.net/seubanco"
PORT=5000
```

Em seguida, execute:

```bash
npx prisma generate
npm start
```

A API estará rodando em `http://localhost:5000`

### 3. Inicie o frontend

```bash
cd ../frontend
npm install
npm run dev
```

A interface estará acessível em `http://localhost:5173`

## ✅ Funcionalidades

- Criar usuários  
- Excluir usuários  
- Integração completa via API REST  

## 📄 Licença

MIT

---

Feito com 💻 por [GustavoVLQ](https://github.com/GustavoVLQ)
