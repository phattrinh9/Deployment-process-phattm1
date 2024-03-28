# Pipeline Process

This application integrates with CircleCI for its deployment pipeline:

- CircleCI triggers events upon code changes from GitHub.
- Environment setup is initiated.
- Environment variables are prepared.
- Node.js is installed.
- Elastic Beanstalk CLI is configured.
- AWS CLI is installed.
- AWS Access Key ID is configured.
- Code is checked out from the repository.
- Front-end dependencies are installed.
- Back-end dependencies are installed.
- Front-end application is built.
- Back-end application is built.
- Front-end app is deployed to Amazon S3.
- Back-end app is deployed to Elastic Beanstalk.