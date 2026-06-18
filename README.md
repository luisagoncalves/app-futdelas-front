# App Fut Delas

Projeto frontend desenvolvido com Next.js.

## Tecnologias

- [Next.js 16](https://nextjs.org)
- [React](https://react.dev)
- [TypeScript](https://www.typescriptlang.org)
- [Jest](https://jestjs.io) + [Testing Library](https://testing-library.com)
- [Cypress](https://www.cypress.io)
- [Husky](https://typicode.github.io/husky) + [Commitlint](https://commitlint.js.org)

## Pré-requisitos

- [Node.js v24.11.1](https://nodejs.org) (via [nvm](https://github.com/nvm-sh/nvm))
- [Docker](https://www.docker.com) (opcional)

## Instalação

```bash
# Use a versão correta do Node
nvm use

# Instale as dependências
npm install
```

## Rodando o projeto

```bash
npm run dev
```

Acesse [http://localhost:3000](http://localhost:3000).

## Rodando com Docker

```bash
docker build -t app-futdelas-front .
docker run -p 3000:3000 -v $(pwd):/app -v /app/node_modules app-futdelas-front
```

## Testes

```bash
# Testes unitários
npm test

# Testes em modo watch
npm run test:watch

# Testes E2E com Cypress
npx cypress open
```