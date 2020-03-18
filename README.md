# Udagram Cloud Formation Project - Udacity DevOps Engineer ND

<p align="center">
  <a href="https://github.com/derrynEdwards/udacitycloudformationproject">
    <img src="Udacity Project - Udagram AWS Infrastructure.jpeg" alt="Diagram" width=1280 height=720>
  </a>
</p>

## About
This project is based on the Udacity DevOps Engineer ND Project - Deploy a high-availability web app using CloudFormation
Using AWS CloudFormation we deploy all the required resources to have a high-availability web app running on AWS.

## Pre-Requisites
- AWS CLI - https://aws.amazon.com/cli/
- AWS CLI Configured with Your AWS Account
- AWS S3 Bucket with Source Code for the Web App
  
## Usage
- Get your parameters ready in udagramparams-server-sample.json and udagramparams-network-sample.json parameters files.
- Run the create.sh script to create the CloudFormation stack on your AWS Account.

```./create.sh {stack-name} {template-file} {params-file}```

Example:

```./create.sh udagram-network udagram-network.yml udagramparams-network-sample.json```

You can also use the update.sh script in order to update your CloudFormation stacks.

Sample URL: http://udaci-WebAp-MMZVFFZD3TLG-465604347.us-west-2.elb.amazonaws.com
