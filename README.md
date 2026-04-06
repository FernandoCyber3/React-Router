# 🧭 Navegação com React Router

Projeto focado em implementar navegação em aplicações React utilizando o React Router. Abordamos desde a criação de rotas simples até rotas com parâmetros, Search Params, navegação programática, Layout Routes e uma página de erro 404 personalizada.

---

## 🛠️ Tecnologias Utilizadas

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## ✨ Funcionalidades

- 🗺️ **Roteamento com React Router** — navegação entre páginas sem recarregamento
- 🔗 **Rotas com Parâmetros** — passagem de dados dinâmicos pela URL
- 🔍 **Search Params** — filtros dinâmicos via parâmetros de busca na URL (`useSearchParams`)
- 🧭 **Navegação Programática** — redirecionamento via código com `useNavigate`
- 🖼️ **Layout Routes** — compartilhamento de layout entre páginas
- ❌ **Página 404** — tratamento de rotas inválidas com página de erro personalizada

---

## 📦 Instalação e Execução

### Pré-requisitos
- Node.js v18+

### Passo a Passo

**1. Clone o repositório:**
```bash
git clone https://github.com/FernandoCyber3/React-Router.git
cd Projeto-react-router
```

**2. Instale as dependências:**
```bash
npm install
```

**3. Inicie o servidor de desenvolvimento:**
```bash
npm run dev
```

> A aplicação estará disponível em: http://localhost:5173

---

## 📚 Conceitos Abordados

### 🔗 Rotas com Parâmetros
Passagem de dados dinâmicos pela URL, como IDs de produtos ou categorias:

### 🔍 Search Params
Filtros dinâmicos utilizando `useSearchParams` para recuperar parâmetros da URL:


### 🧭 Navegação Programática
Redirecionamento via código utilizando o hook `useNavigate`, sem depender de links:
```tsx
const navigate = useNavigate()
navigate("/home")
```

### 🖼️ Layout Routes
Compartilhamento de componentes comuns (como Header e Footer) entre múltiplas páginas usando rotas de layout.

### ❌ Página 404
Rota coringa para capturar acessos a URLs inválidas e exibir uma página de erro amigável ao usuário.
