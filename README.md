# Udagram-App

## Getting Started

1. Clone this repo[reem-udagram](https://github.com/reemsakr/reem_udagram)locally into the location of your choice.
2. Open a terminal and navigate to the root of the repo
3. follow the instructions in the installation steps.
4. link to hosted frontend application[udagram-frontend](http://reem-udagram2.s3-website-us-east-1.amazonaws.com)

## App Dependencies

```
- Node v14.15.1 (LTS) or more recent.
- npm 6.14.8 (LTS) or more recent..
- AWS CLI v2.
- A RDS database running Postgres.
- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. In AWS, provision a publicly available RDS database running Postgres.
1. In AWS, provision a s3 bucket for hosting the uploaded files.
1. Export the ENV variables needed or use a package like [dotnev](https://www.npmjs.com/package/dotenv)/.
1. From the root of the repo, navigate udagram-api folder `cd udagram/udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
1. Without closing the terminal in step 1, navigate to the udagram-frontend `cd udagram/udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd udagram/udagram-frontend`
1. `npm run test`
1. `npm run e2e`

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## resources:

- udacity classroom.
- youtube tutorials.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)