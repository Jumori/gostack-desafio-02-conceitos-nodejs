# Challenge 02: Node.js Concepts Resolution
Challenge from **GoStack Bootcamp**

## About the challenge
The purpose of this challenge is to apply the initial concepts of Node.js by developing and application that stores repositories of your portfolio, that will allow you to list, update, and delete repositories, and besides that, the repository can also receive likes.

For more information about the original challenge, access the repository: [Challenge 02: Node.js Concepts](https://github.com/rocketseat-education/bootcamp-gostack-desafios/tree/master/desafio-conceitos-nodejs).


## Application routes
* `POST /repositories`: This route creates a new repository. It must receive `title`, `url` and `techs` inside the request body.
* `GET /repositories`: This route lists all repositories.
* `PUT /repositories/:id`: This route changes only `title`, `url` and `techs` of the repository that has the `id` equal to the `id` present in the route params.
* `DELETE /repositories/:id`: This route deletes a repository with the same `id` from route params.
* `POST /repositories/:id/like`: This route increases the number of likes from a chosen repository through the `id` param present in the route params.

## How to use
1. Clone this repository
2. Run `yarn` command at the project folder to install all dependencies
3. To start a local server, run the command `yarn dev` at the project folder
4. To run the automated tests, run the command `yarn test`