# Infrastructure Overview

## Components

- **udagram-api**: This service provides application functionalities through API calls.
- **udagram-frontend**: An Angular-based application that displays the UI and communicates with the dagram-api to send and receive requests.

## AWS Hosting Details

- **Front-end**: Hosted on Amazon S3.
- **Back-end**: Deployed on Elastic Beanstalk (EB).
- **Database**: Data is stored in a Postgres database managed by Amazon RDS.