# Resolução do Desafio 02: Conceitos do Node.js
Desafio proposto durante o **Bootcamp GoStack**

## Sobre o desafio
A proposta deste desafio é aplicar os conceitos iniciais de Node.js para desenvolver uma aplicação que armazena repositórios do portifólio que irá permitir a criação, listagem, atualização e remoção dos repositórios, e, além disso, permitir que os repositórios recebam "likes".

Para mais informações sobre o desafio proposto, acesse o repositório do desafio: [Desafio 02: Conceitos do Node.js](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs).

## Rotas da aplicação
* `POST /repositories`: Rota que cria um novo repositório. A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição.
* `GET /repositories`: Rota que lista todos os repositórios.
* `PUT /repositories/:id`: Rota que altera `title`, `url` e `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros.
* `DELETE /repositories/:id`: Rota que deleta o repositório com o `id` igual ao presente nos parâmetros.
* `POST /repositories/:id/like`: Rota que aumenta o número de likes do repositório escolhido através do `id` presente nos parâmetros da rota.

## Como usar
1. Clone este repositório
2. Execute o comando `yarn` na pasta do projeto clonado para instalar todas as dependências
3. Para iniciar um servidor local, execute o comando `yarn dev` na pasta do projeto
4. Para executar os testes automatizados, execute o comando `yarn test`