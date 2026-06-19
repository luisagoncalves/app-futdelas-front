# App Fut Delas

Projeto frontend desenvolvido com Next.js.

## Tecnologias

- [Next.js 16](https://nextjs.org)
- [React](https://react.dev)
- [TypeScript](https://www.typescriptlang.org)
- [Jest](https://jestjs.io) + [Testing Library](https://testing-library.com)
- [Stryker](https://stryker-mutator.io)
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
docker compose up --build
# Ou
docker compose up
```

## Testes

```bash
# Testes unitários
npm test

# Testes em modo watch
npm run test:watch

# Testes de mutação
npm run test:mutation

# Testes E2E com Cypress
npx cypress open
```

## Padrão de commits

Este projeto usa [Conventional Commits](https://www.conventionalcommits.org):
