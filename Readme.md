# bootcamp2021c08 - Introduction to Serverless and Cloud Computing using CDK - AWS CDK, Lambda and CDN Website Deployment - AWS CDK Hello World

## AWS CDK Hello World
- setup cdk app
- create s3 bucket
- Deploy cdk app
- Destroy cdk app
- cdk config on system

## Class Notes

Working with cloud have a major issue of lockin where we are stuck with same cloud provider. kubernetes was one of the solution to this issue but working on a large scale is not possible with out using cloud as it provides the major benifit of scalability.

## How to use AWS CDK

- Signup to AWS
- Create IAM user
  - Navigate to IAM section of the services.
  - Select users from access management
  - Select user name and grant programmatic access
  - Add to a group or create new with permissions
  - Tags (optional)
  - Review and create user
  - At the end access key and id will be generated
- Install TypeScript
  - "npm install -g typescript"
- Install AWS CLI
  - Download and install from [here](https://awscli.amazonaws.com/AWSCLIV2.msi)
  - "aws --version"
- Install AWS SAM CLI
  - Create AWS account
  - Create IAM user
  - Install docker
    - [Downlaod](https://docs.docker.com/docker-for-windows/install/)
    - Configure shared drives
    - "docker ps"
  - Install CLI
    - [Downalod](https://github.com/aws/aws-sam-cli/releases/latest/download/AWS_SAM_CLI_64_PY3.msi)
    - "sam --version"
  - Install Git
- Install AWS CDK

  - "aws configure"
  - "npm install -g aws-cdk"
  - "cdk --version"

## Reading Material

- [AWS Free Tier](https://aws.amazon.com/free/)
- [Step 00: Hello CDK](https://github.com/panacloud-modern-global-apps/full-stack-serverless-cdk/tree/main/step00_hello_cdk)
- [Step 01: Hello Lambda](https://github.com/panacloud-modern-global-apps/full-stack-serverless-cdk/tree/main/step01_hello_lambda)

## Sections

- [Hello CDK](./step00_hello_cdk)
- [Hello Lambda](./step01_hello_lambda)

## Class 8 Videos: AWS CDK Hello World

- [English YouTube](https://www.youtube.com/watch?v=yyuQ6f6znXc&ab_channel=PanacloudCloudAI%2CIoT%2CandBlockchainCourse)
- [English Facebook](https://www.facebook.com/fb.anees.ahmed/videos/261780865432466)
- [Urdu YouTube](https://www.youtube.com/watch?v=kiOcVAPwlzQ&ab_channel=PanacloudUrduCloudAICourse)
- [Urdu Facebook](https://www.facebook.com/Ai.SirQasim/videos/204372268374467)
