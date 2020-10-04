<h1 align="center">
  Resolução do Desafio 02: Conceitos do Node.js
</h1>

<h3 align="center">
  Desafio proposto durante o Bootcamp GoStack
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Jumori/gostack-desafio-conceitos-nodejs?color=%2304D361">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Jumori/gostack-desafio-conceitos-nodejs">

  <a href="https://github.com/Jumori/gostack-desafio-conceitos-nodejs/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Jumori/gostack-desafio-conceitos-nodejs">
  </a>
    
   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
 
</p>

<h4 align="center">
	🚧 Concluído 🚧
</h4>

## Tabela de Conteúdos
<!--ts-->
  * [Sobre o desafio](#-sobre-o-desafio)
  * [Features](#️-features)
  * [Como usar](#-como-usar)
    * [Pré-requisitos](#pré-requisitos)
    * [Instalação](#instalação)
    * [Rodando o back-end](#rodando-o-back-end-servidor)
  * [Tecnologias utilizadas](#-tecnologias-utilizadas)
  * [Autora](#h2-idautora-80autorah2)
  * [Licensa](#h2-idlicensa-77licensah2)
<!--te-->

## 💻 Sobre o desafio
A proposta deste desafio é aplicar os conceitos iniciais de Node.js para desenvolver uma aplicação que armazena repositórios do portifólio que irá permitir a criação, listagem, atualização e remoção dos repositórios, e, além disso, permitir que os repositórios recebam "likes".

Para mais informações sobre o desafio proposto, acesse o repositório do desafio: [Desafio 02: Conceitos do Node.js](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs).

## ⚙️ Features
- [x] `POST /repositories`: Rota que cria um novo repositório. A rota deve receber `title`, `url` e `techs` dentro do corpo da requisição.
- [x] `GET /repositories`: Rota que lista todos os repositórios.
- [x] `PUT /repositories/:id`: Rota que altera `title`, `url` e `techs` do repositório que possua o `id` igual ao `id` presente nos parâmetros.
- [x] `DELETE /repositories/:id`: Rota que deleta o repositório com o `id` igual ao presente nos parâmetros.
- [x] `POST /repositories/:id/like`: Rota que aumenta o número de likes do repositório escolhido através do `id` presente nos parâmetros da rota.

## 🚀 Como usar

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
* [Node.js](https://nodejs.org/en/)
* [Yarn](https://yarnpkg.com/)

### Instalação
1. Clone este repositório
2. Execute o comando `yarn` na pasta do projeto clonado para instalar todas as dependências

### Rodando o back-end (servidor)
1. Para iniciar um servidor local, execute o comando `yarn dev` na pasta do projeto. Este servidor poderá ser acessado via `localhost:3333`
2. Para executar os testes automatizados, execute o comando `yarn test`

## 🛠 Tecnologias utilizadas
As seguintes ferramentas foram usadas na construção do projeto:

#### **Server**  ([NodeJS](https://nodejs.org/en/))
- **[Express](https://expressjs.com/)**
- **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
- **[UUIDV4](https://www.npmjs.com/package/uuidv4)**

  
## 🦸‍♀️ Autora
<img style="border-radius: 50%;" src="https://avatars1.githubusercontent.com/u/44618499?s=400&u=691cddb486d4b665417d25d8a575e508d6ef9563&v=4" width="100px;" alt=""/>
<br />
<sub><b>Juliana Morikoshi</b></sub>

Feito com ❤️ por Juliana Morikoshi 👋 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-Juliana-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/julianamorikoshi/)](https://www.linkedin.com/in/julianamorikoshi/) 
[![Gmail Badge](https://img.shields.io/badge/-julianamorikoshi@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:julianamorikoshi@gmail.com)](mailto:julianamorikoshi@gmail.com)

## 📝 Licença
Esse projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.