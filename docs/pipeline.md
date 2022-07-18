## Continuous Integration

#### GitHub

Github is used by developers to control versions of the code, by linking github and circleci the github will triggre circleci to start CI/CD code.

#### CircleCI

CircleCI is used for automatic run scripts using folder .circleci/config.yml alloctaed in udagram-frontend & udagram-server

#### added enviroement to circleci

- AWS_ACCESS_KEY_ID
- AWS_DEFAULT_REGION
- AWS_SECRET_ACCESS_KEY

#### used scripts to pipeline the project

- `npm run frontend:install` - To install frontend dependencies.
- `npm run frontend:build` - To build the Angular/Frontend.
- `npm run backend:install` - To install backend dependencies.
- `npm run backend:build` - To build the backend application.
- `npm run backend:deploy` - To deploy front end and backend to aws services

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `npm run test`
2. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.
