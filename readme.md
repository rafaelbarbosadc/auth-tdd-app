![alt text](https://miro.medium.com/max/918/1*adYdrfOLy0T5oW02kTvsqg.png)

## Tests with Jest

I'm using Jest with Faker and Factory Girl to test a Express + JWT application.

## Install

- Docker container: `docker run --name tdd -e POSTGRES_USER=docker -e POSTGRES_PASS=docker -e POSTGRES_DBNAME=tdd -p 5432:5432 -d -t kartoza/postgis`

- Install dependencies: `yarn install`

- Make migrations: `yarn sequelize db:migrate`

- Run the tests: `yarn test`

## Tests

Tests are located in `__tests__` folder. After you run the tests, you can visualize the coverage results in a browser in `__tests__/coverage/lcov-report/index.html`
