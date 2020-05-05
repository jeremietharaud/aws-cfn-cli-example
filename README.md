# aws-cfn-cli-example

This repository contains an example of a CI/CD pipeline in CircleCI for deploying a CloudFormation stack using [aws-cfn-cli](https://github.com/jeremietharaud/aws-cfn-cli).

In `.circleci/config.yml` file, you will find the workflow for deploying the CFN stack `private-dns.yaml` (which creates a private hosted zone).