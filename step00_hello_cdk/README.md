# Step00 Hello CDK

## Steps to compile code

Create folder

```
mkdir step00_hello_cdk
cd step00_hello_cdk
```

create app

```
cdk init app --language typescript
```

Buld app

```
npm run watch
```

Check stacks list

```
cdk ls
```

Install S3 bucket

```
npm install @aws-cdk/aws-s3
```

Update lib/step00_hello_cdk-stack.ts

```
new s3.Bucket(this, 'MyFirstBucket', {
      versioned: true,
      removalPolicy: cdk.RemovalPolicy.DESTROY,
      autoDeleteObjects: true,
    });
```

Synthesize an AWS CloudFormation template for the app

```
cdk synth
```

Deploy the App

```
cdk deploy
```

Destroy App

```
cdk destroy
```

## Reading Materail

- [What is AWS CDK?](https://serverless-stack.com/chapters/what-is-aws-cdk.html)
- [AWS CDK in TypeScript](https://docs.aws.amazon.com/cdk/latest/guide/work-with-cdk-typescript.html)
- [AWS CDK and Typescript: Deploy a static React app to S3](https://medium.com/swlh/aws-cdk-and-typescript-deploy-a-static-react-app-to-s3-df74193e9e3d)
- [Signup for a AWS Fee Tier](https://aws.amazon.com/free/)
- [Get and setup AWS Credentials](https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/aws-credentials.html)
- [Create IAM User](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started_create-admin-group.html)
- [Install TypeScript](https://www.npmjs.com/package/typescript)
- [Install AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html)
- [Installing the AWS SAM CLI - This is an AWS CLI tool that helps you develop, test, and analyze your serverless applications locally](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)
- [Install AWS CDK](https://docs.aws.amazon.com/cdk/latest/guide/work-with-cdk-typescript.html)
- [Install Docker to test apps locally](https://docs.docker.com/get-docker/)
- [Install the Toolkit for VS Code](https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/setup-toolkit.html)
- [Understand the key concepts: app, stacks, constructs, L1, L2, and L3 constructs](https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html)
- [Build a Hello World App](https://docs.aws.amazon.com/cdk/latest/guide/hello_world.html)

## Welcome to your CDK TypeScript project!

This is a blank project for TypeScript development with CDK.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Useful commands

- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template
