✨ Tecnologias
Esse projeto foi desenvolvido com as seguintes tecnologias:

Node.js
Typescript
Serverless Framework
Puppeteer
Amazon Lambda
💻 Projeto
O projeto tem como responsabilidade gerar um certificado para um usuário e a possibilidade de pesquisar a validade de um certificado.

🚀 Como executar
Clone o repositório e acesso o diretório
Para rodar localmente
Rode yarn para instalar as dependências
Rode yarn dynamodb:install para baixar o DynamoDB localmente
Rode yarn dynamo:start para iniciar o banco de dados em ambiente local
Rode, em outro terminal, o yarn dev para iniciar a aplicação em ambiente local
Para fazer o deploy
Configurar as credenciais do usuário
Rode yarn deploy para subir o projeto para AWS Lambda


### Install dependencies
```
npm i
```

### Run application
```
npm run dynamodb:install

npm run dynamodb:start && npm run dev
```

### Deploy application to your favorite provider (this application using aws)
```
serverless config credentials —provide aws —key=YOUR_KEY —secret=YOUR_SECRET -o 

npm run deploy:dev (dev)
npm run deploy:prod (production)
```
