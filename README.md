# CRUD com Angular

- Angular: 9.1.12
- Node: 12.18.3

## Backend

Feito em JSON server

* npm init -y (aqui ele criar um arquivo package.json para mim)
* Adiciono a extensão json-server: `npm i json-server`
* Crio o arquivo da minha API, no caso é o `db.json`
* Agora, eu tenho que colocar em `package.json` o script e as especificações que eu quero para rodar o server:
    - "start": "json-server --watch db.json --port 3001" 
    (eu quero que ao iniciar o server `(npm start)` ele fique olhando qualquer alteração que eu fizer no arquivo `db.json` e estou sentando para que ele faça isso na porta 3001)

## Frontend

## Instalação

Na pasta `backend` digite o comando:

`npm install`

Dessa forma ele instalará todas as dependências necessárias para o projeto.

## Como rodar o projeto

Aqui vamos ver como executar o projeto e ver ele funcionando na prática.

### Backend

Dentro da pasta `backend` dê o comando `npm start` que irá subir um servidor para a API criada.

Para verificar os dados da API, acesse o link: http://localhost:3001/products

### Frontend

Para iniciar minha App, dentro da pasta `frontend` digite o comando `npm start`

## Como criar componentes

Para criar um componente no Angular, você precisa dar o comando `ng generate component nome_do_componente` ou `ng g c nome_do_componente`.



