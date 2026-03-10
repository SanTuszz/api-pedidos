![Node.js](https://img.shields.io/badge/Node.js-18-green)
![Express](https://img.shields.io/badge/Express-Framework-black)
![Swagger](https://img.shields.io/badge/Swagger-API%20Docs-brightgreen)
![Status](https://img.shields.io/badge/status-concluído-success)

# 🧾 API de Pedidos
<img width="1598" height="633" alt="swagger" src="https://github.com/user-attachments/assets/ccc0c781-6041-41da-88fb-e5378346ac42" />


API REST desenvolvida com **Node.js** e **Express** para gerenciamento de pedidos.  
Este projeto foi criado com fins de estudo e demonstra conceitos básicos de construção de APIs.

---

# 🚀 Tecnologias utilizadas

- Node.js
- Express
- JavaScript

---

# 📦 Funcionalidades

✔ Criar pedidos  
✔ Listar todos os pedidos  
✔ Buscar pedido por ID  
✔ Atualizar pedido  
✔ Remover pedido  

---

# 🔗 Rotas da API

## Criar pedido
POST /orders

## Listar pedidos
GET /orders

## Buscar pedido por ID
GET /orders/:id

## Atualizar pedido
PUT /orders/:id

## Remover pedido
DELETE /orders/:id

---

# ⚙️ Como executar o projeto

### 1️⃣ Clone o repositório

```
git clone https://github.com/SanTuszz/api-pedidos.git
```

### 2️⃣ Entre na pasta do projeto

```
cd api-pedidos
```

### 3️⃣ Instale as dependências

```
npm install
```

### 4️⃣ Execute o servidor

```
node index.js
```

O servidor será iniciado em:

```
http://localhost:3000/api-docs/
http://localhost:3000
```

---

# 📌 Exemplo de requisição (JSON)

Criar pedido:

```json
{
  "cliente": "Douglas",
  "produto": "Notebook",
  "quantidade": 1
}
```

---

# 👨‍💻 Autor

Desenvolvido por **Douglas Santos**
