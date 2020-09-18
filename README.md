# Resolução do Desafio 05: Primeiro projeto Node.js
Desafio proposto durante o **Bootcamp GoStack**

## Sobre o desafio
A proposta deste desafio é criar uma aplicação para armazenar transações financeiras de entrada e saída, permitindo a criação de uma transação e a listagem das mesmas. O desenvolvimento desta aplicação coloca em prática os conhecimentos adquiridos em Node.js e TypeScript, utilizando conceitos de models, repositories e services.

Para mais informações sobre o desafio proposto, acesse o repositório do desafio: [Desafio 05: Primeiro projeto Node.js](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-fundamentos-nodejs).

## Rotas da aplicação
* `POST /transactions`: Rota que cria uma nova transação. A rota deve receber `title`, `value` e `type` dentro do corpo da requisição, sendo `type` do tipo `income` ou `outcome`.
* `GET /transactions`: Rota que lista toda as transações registradas junto com o valor da soma de entradas, retiradas e o total de crédito disponível.

## Como usar
1. Clone este repositório
2. Execute o comando `yarn` na pasta do projeto clonado para instalar todas as dependências
3. Para iniciar um servidor local, execute o comando `yarn dev` na pasta do projeto
4. Para executar os testes automatizados, execute o comando `yarn test`
