# 🛍️ Projeto Final – Desenvolvimento Front-end II

Este repositório contém o projeto final desenvolvido para a disciplina **Desenvolvimento Front-end II**.  
O objetivo é criar um website com três páginas (Início, Usuários e Produtos), incluindo integração com API pública, formulários, validações e manipulação dinâmica de dados.

---

## 🚀 Funcionalidades Implementadas

### 🔹 Página Inicial (`index.html`)
- Navegação para Usuários e Produtos  
- Layout simples e responsivo  

### 🔹 Página de Usuários (`/users/users.html`)
- Listagem inicial carregada da API **DummyJSON**
- Adicionar usuário com validações
- Remover usuário da lista
- Campos: nome, sobrenome, email, idade e foto (URL)

### 🔹 Página de Produtos (`/products/products.html`)
- Listagem inicial via API DummyJSON
- Formulário para adicionar produtos
- Remoção de produtos da lista
- Campos: título, descrição, preço, marca, categoria e thumbnail

---

## 🌐 API Pública Utilizada

**DummyJSON**  
- Usuários: `https://dummyjson.com/users`  
- Produtos: `https://dummyjson.com/products`

Campos remapeados para o projeto:

| API               | Projeto     |
|------------------|-------------|
| firstName        | nome        |
| lastName         | sobrenome   |
| email            | email       |
| age              | idade       |
| image            | foto        |
| title            | título      |
| description      | descrição   |
| price            | preço       |
| brand            | marca       |
| category         | categoria   |
| thumbnail        | foto        |

---

## 🧪 Validações Implementadas

### ✔ Campos de texto
- 3 a 50 caracteres  
- Obrigatórios

### ✔ Email
- Regex válida recomendada pela instrução

### ✔ Números
- Idade e preço: **> 0 e < 120**

### ✔ URLs (fotos)
- Validação opcional de URL

---

## 📁 Estrutura do Projeto
/assets
/css/styles.css

/users
users.html
users.js

/products
products.html
products.js

index.html
main.js


---

## 🌐 Hospedagem — GitHub Pages

O projeto está hospedado via GitHub Pages.

Acesse:  



(Atualize com o seu link real após publicar.)

---

## ▶️ Vídeo de Demonstração

O vídeo deve apresentar:
- Funcionamento das três páginas  
- Navegação entre telas  
- Adição e remoção de itens  
- Listagem carregada da API  
- Validações em ação  

---

## 👥 Integrantes do Grupo
(Adicione aqui os nomes do grupo, se houver)

---

## 🛠️ Como executar localmente

### ✔ Método 1 – Abrir direto
Abra o arquivo:


index.html


### ✔ Método 2 – VS Code + Live Server (recomendado)
1. Abra o projeto no VS Code  
2. Clique com o botão direito em `index.html`  
3. Selecione **Open with Live Server**

---

## 📌 Observação
As operações de adição/remoção são simuladas **localmente**, pois a API pública não grava alterações.

---

### ✨ Projeto desenvolvido para fins acadêmicos – Front-end II

