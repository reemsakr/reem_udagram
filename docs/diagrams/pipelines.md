# Pipeline documentation

- we use CircleCi as our pipeline the config file found at *.circleci/config.yml*


## The config file has the following flows

- Frontend
    - Install
    - Build
    - Deploy
- Backend
    - Install
    - Build
    - Deploy

- GitHub :is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.


- CircleCI: .CircleCI is the world’s largest shared continuous integration and continuous delivery (CI/CD) platform, and the central hub where code moves from idea to 

  delivery.


- Frontend: Executes the package.json file's build script. The assets are then uploaded to S3 using the AWS CLI.

- Backend: Runs the build script, then exports all CircleCI setup environment variables to a.env file before running the archive script. The archive is then uploaded to     
  S3 using AWS CLI.