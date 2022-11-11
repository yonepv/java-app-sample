# java-app-sample

This project to work on pipelines models. Specifically starting with AWS pipelines.

Prérequis:
- AWS account
  - IAM: Role, policy
  - Secrets Manager: key for Snyk account connection
  - S3: bucket for build output
  - CodeBuild: build project
  - CodePipeline: pipeline
- Sources in Dépôt Git
  - build spec file in ./aws/workflows directory
- Connection to third party Snyk for the scan.
  - Snyk API key in the AWS Secrets Manager

## AWS CodeBuild User Guide

[Getting started with AWS CodeBuild using the console](https://docs.aws.amazon.com/codebuild/latest/userguide/getting-started.html)