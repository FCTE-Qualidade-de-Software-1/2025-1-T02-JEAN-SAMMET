# 🌾 AgroMart Web

Este repositório contém o código-fonte do front-end da aplicação **AgroMart**, uma plataforma focada na inclusão de agricultores com baixa alfabetização textual e digital. O projeto utiliza tecnologias modernas como **React**, **TypeScript**, **Vite** e **Tailwind CSS** para proporcionar uma experiência de usuário simples, acessível e visualmente intuitiva.

---

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://github.com/colinhacks/zod)
- [Axios](https://axios-http.com/)

---

## 📦 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- [Git](https://git-scm.com/)
- [Node.js (v18+ recomendado)](https://nodejs.org/)
- [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)

---

## 🛠️ Como rodar o projeto localmente

Siga os passos abaixo para executar o AgroMart Web no seu ambiente de desenvolvimento local.

### 1. Clone o repositório

```bash
git clone https://github.com/AgroMart/agromart-web.git
cd agromart-web
 ```

### 2. Instale as dependências
Com npm:

```bash
npm install
```

Ou com yarn:

```bash
yarn install
```

### 3. Configure as variáveis de ambiente
Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

```bash
VITE_API_BASE_URL=http://localhost:3333
```

⚠️ Certifique-se de que o back-end da aplicação esteja rodando nesse endereço. Caso contrário, ajuste conforme necessário.

### 4. Execute o projeto

```bash
npm run dev
```

Ou:

```bash
yarn dev
```

Acesse http://localhost:5173 para visualizar a aplicação em execução.

## 🧪 Rodando os testes
O projeto pode conter testes automatizados. Para executá-los, utilize:

```bash
npm test
```

Ou:

```bash
yarn test
```

## 📦 Build para Produção
Para gerar a versão de produção do projeto:

```bash
npm run build
```

Ou:

```bash
yarn build
```

E para pré-visualizar o build:

```bash
npm run preview
```

Ou:

```bash
yarn preview
```