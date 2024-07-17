# Cloud Resume Challenge

This project is part of the Cloud Resume Challenge. It includes a static resume website deployed on AWS with a visitor counter.

## Features

- Static website hosted on Amazon S3
- CloudFront distribution for HTTPS
- Visitor counter using JavaScript
- Backend API with AWS API Gateway and Lambda
- Visitor count stored in DynamoDB
- Infrastructure as Code using AWS SAM
- CI/CD with GitHub Actions

## Getting Started

### Prerequisites

- AWS Account
- AWS CLI
- AWS SAM CLI
- GitHub Account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/llam88/cloud-resume.git
   cd cloud-resume
   ```

2. Deploy the infrastructure:
   ```bash
   sam build
   sam deploy --guided
   ```

### License

This project is licensed under the MIT License.
