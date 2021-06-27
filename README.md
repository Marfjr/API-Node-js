# api-node-js

PARA CORRETO FUNCIONAMENTO, ABAR O TERMINAL DENTRO DA PASTA "api-node-js" e digite "npm install" e tecle enter.

APOS A INSTALAÇÃO, COM O TERMINAL ABERTO DENTRO DA PASTA "api-node-js", digite "nodemon start" para rodar a API

Para testar os metodos POST, GET, DELETE
Utilize o Postman ou semelhante para testar os metodos

GET
http://localhost:21262

POST
http://localhost:21262/add
{
    "6": {
        "Nome": "Cliente 6",
        "Idade": "6"
    }
}

DELETE
http://localhost:21262/2
Utilize GET novamente para confirmar que o id 2 foi excluido.



Dependencias instaladas

npm init

npm install express

npm install body-parser

npm i morgan
 
npm i cors

npm i nodemon

