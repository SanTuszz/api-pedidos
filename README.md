# 🧾 API de Pedidos

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
