**How to Create Serverless Aurora cluster with AWS CDK**

Read more [here](https://www.almirzulic.com/2019/08/14/create-serverless-aurora-instance-with-cdk/).

### Instructions 

You'll need an Amazon Web Services account and credentials set up on your development machine. If you haven't done it before, here's a useful guide for [Configuring the AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html).

- Install [NodeJS](https://nodejs.org) 
- Install [AWS CDK](https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html) framework using `npm i -g aws-cdk`
- Clone this repository `git clone https://github.com/bind-almir/cdk-aurora-serverless.git`
- Install dependencies `npm i`
- Build project `npm run build`
- Deploy `account=YOUR_ACCOUNT_NUMBER region=YOUR_REGION cdk deploy` 

# Useful commands

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
