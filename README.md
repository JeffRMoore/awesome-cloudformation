# awesome-cloudformation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome curated list of AWS CloudFormation links

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

- [AWS Documentation](#aws)
- [Articles](#articles)
  - [CodePipeline](#CodePipelineArticles)
- [Examples](#examples)
  - [CodePipeline](#CodePipelineExamples)
  - [Cognito](#CognitoExamples)
  - [Lambda](#LambdaExamples)
  - [Serverless Application Model (SAM)](#ServerlessApplicationModelExamples)

<!-- /MarkdownTOC -->

<a name="aws" />
## AWS Documentation

* [User Guide](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html) - AWS Official User Guide
* [API Reference](http://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/Welcome.html) - AWS Official API Reference

<a name="articles" />
## Articles

### CodePipeline
<a name="CodePipelineArticles" />
[Build Continuous Delivery Workflows for CloudFormation Stacks](https://aws.amazon.com/blogs/aws/codepipeline-update-build-continuous-delivery-workflows-for-cloudformation-stacks/) - 
describes how to setup a continuous delivery workflow for deploying CloudFormation Templates using CloudFormation.

<a name="examples" />
## Examples

[AWS CloudFormation Template Collection](https://github.com/awslabs/aws-cloudformation-templates) - Officially supported 
and community contributed AWS sample templates.

[User Guide Sample Templates](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-sample-templates.html) -
Sample templates from the CloudFormation User Guide.

<a name="CodePipelineExamples" />
### CodePipeline
[Continuous Deployment Reference Architecture] (https://github.com/awslabs/ecs-refarch-continuous-deployment) - Reference Architecture for creating a flexible and scalable deployment pipeline to Amazon ECS using AWS CodePipeline.  Demonstrates
a GitHub CodePipeline source and a PHP application with an ECS cluster and load balancer.

[Continuous Delivery Basic Walkthrough](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide//continuous-delivery-codepipeline-basic-walkthrough.html) -
CloudFormation userguide walkthrough of setting up a CodePipeline for Continuous delivery that uses a CloudFormation
stack to deploy a separate CloudFormation stack.

<a name="CognitoExamples" />
### Cognito
[AWS API Gateway Developer Portal](https://github.com/awslabs/aws-api-gateway-developer-portal) - An example serverless application deployment with Cognito and Lambda configuration in CloudFormation.

<a name="LambdaExamples" />
### Lambda
[Serverless Image Resizing](https://github.com/awslabs/serverless-image-resizing) - An image resizing API deployed
with CloudFormation built on Lambda and API Gateway with S3.

<a name="ServerlessApplicationModelExamples" />
### Serverless Application Model (SAM)
[Startup Kit Serverless Workload](https://github.com/awslabs/startup-kit-serverless-workload) - An example serverless RESTful API, to be deployed via the AWS Serverless Application Model (SAM).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Jeff Moore has waived all copyright and related or neighboring rights to this work.
