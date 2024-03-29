# Hosting a Full-Stack Application

# Udagram

## Overview

The Udagram application serves as an alternative starting point for this project if you prefer not to deploy your own code from previous courses within this nanodegree. Udagram is a simplified Full-Stack web application encompassing all essential components.

## Hosting Link

[Visit Udagram](http://udacityp4phattm1-ver1.s3-website-us-east-1.amazonaws.com)

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Environment Variables Setup

Ensure the following environment variables are configured:

- `AWS_ACCESS_KEY_ID`
- `AWS_DEFAULT_REGION`
- `AWS_SECRET_ACCESS_KEY`
- `AWS_SESSION_TOKEN`
- `JWT_SECRET`
- `POSTGRES_DB`
- `POSTGRES_HOST`
- `POSTGRES_PASSWORD`
- `POSTGRES_PORT`
- `POSTGRES_USERNAME`
- `PORT`
- `URL`

## Installation Steps

To set up the required AWS services for running the application:

1. Navigate to the root directory of the repository.
2. Execute `npm run frontend:install` to install the necessary `node_modules` for the frontend and `npm run api:install` for the backend.
3. Once the installation completes, initiate the API using `npm run api:start` and launch the frontend code with `npm run frontend:start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
