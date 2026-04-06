# 🎬 CRUD de Vídeos com Node.js

Esse é meu primeiro projeto CRUD utilizando **Node.js**, onde desenvolvi uma API para gerenciar vídeos com:

- 📌 título
- 📝 descrição
- ⏱️ duração

---

## 📌 Funcionalidades

A API permite:

- Criar um vídeo
- Listar vídeos
- Buscar vídeos por título
- Atualizar um vídeo
- Deletar um vídeo

---

## 🧠 O que estou aprendendo

- Criação de servidor com Node.js
- Uso do Fastify
- Rotas HTTP (GET, POST, PUT, DELETE)
- Manipulação de dados (req.body e req.params)
- Integração com banco de dados (PostgreSQL)

---

## ⚙️ Tecnologias utilizadas

- Node.js
- Fastify
- PostgreSQL

---

## ▶️ Como rodar o projeto

```bash
git clone https://github.com/Bruno08004/CRUD-Node-JS.git
cd CRUD-Node-JS
npm install
node server.js
```

## 🔥 Estrutura dos dados

Exemplo de um vídeo:

```json
{
  "title": "Meu vídeo",
  "description": "Descrição do vídeo",
  "duration": 120
}
```

---

## 📡 Rotas da API

### ➕ Criar vídeo

```
POST /videos
```

### 📄 Listar vídeos

```
GET /videos
```

Com busca:

```
GET /videos?search=texto
```

### ✏️ Atualizar vídeo

```
PUT /videos/:id
```

### ❌ Deletar vídeo

```
DELETE /videos/:id
```

---

## 💡 Observação

Este é um projeto a nível didático, desenvolvido exclusivamente para fins de aprendizado e testes com requisições HTTP e integração com banco de dados.

---

## 👨‍💻 Autor

Bruno Campos
