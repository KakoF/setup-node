# Setup para Node (TypeScript, ESLint, Jest, Babel)

Setup para inicializar um projeto com alumas dependencias que utilizo

## Depêndencias

```bash
npm install
```

## Bibliotecas de database adicionadas

```bash
@types/express -D
@typescript-eslint/eslint-plugin -D
@typescript-eslint/parser -D
eslint -D
eslint-config-standard -D
eslint-plugin-import -D
eslint-plugin-node -D
eslint-plugin-promise -D
ts-node-dev -D (tsc(typescript para js), node, nodemon)
typescript -D
jest -D

express
```

## Scripts

```bash
run: yarn dev
build: yarn start
test: yarn test
```

## Alguns comandos executados

```bash
Criar migration: yarn typeorm migration:create -n CreateUsersTable
Rodar migration: yarn typeorm migration:run
```
