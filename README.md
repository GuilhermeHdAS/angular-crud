# CRUD com Angular

Angular: 9.1.12
Node: 12.18.3

## Backend

Feito em JSON server

* npm init -y (aqui ele criar um arquivo package.json para mim)
* Adiciono a extensão json-server: npm i json-server
* Crio o arquivo da minha API, no caso é o `db.json`
* Agora, eu tenho que colocar em `package.json` o script e as especificações que eu quero para rodar o server:
    - "start": "json-server --watch db.json --port 3001" 
    (eu quero que ao iniciar o server `(npm start)` ele fique olhando qualquer alteração que eu fizer no arquivo `db.json` e estou sentando para que ele faça isso na porta 3001)

## Frontend

