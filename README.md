# api-node
 criando api com node e apollo

[github api-node](https://github.com/ederPires/api-node)
[Documentação Apollo](https://www.apollographql.com/docs/apollo-server/)

```Javascript

npm init -y // iniciar o projeto

npm i typescript ts-node-dev -D // instalar typescript

npx tsc --init // ativa as configurações

//modificar o package.json
"dev:simple": "tsnd --respawn --transpile-only simple-server.ts" // não faz checagem de tipagem, criar arquivo simple-server

npm i graphql apollo-server // instalar graphql e apollo

// configurar o simple-server

npm run dev:simple // rodar o projeto no modo dev

npm i uuid // Para gerar IDs únicos

```
