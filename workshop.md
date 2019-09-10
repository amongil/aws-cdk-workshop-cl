author: Alvaro Mongil
summary: Deploying cloud infrastructure using the AWS CDK
status: draft
id: aws-cdk-workshop
categories: aws,cdk,typescript,iac
environments: ts
feedback link: https://github.com/amongil/aws-cdk-workshop-cl/issues

# Deploying cloud infrastructure using the AWS CDK

## Introduction
Duration: 5

When defining Infrastructure as Code (IaC) in AWS, writing YAML CloudFormation templates is probably the most common choice among Enterprises. Main reason being that CloudFormation is a first-class service in the AWS ecosystem. It is completely integrated with all the other services in the platform and keeps getting updates and improvements over time.

But YAML is not a programming language and the usual method of collaboration and sharing of templates is copy-pasting existing templates and adapting those to fit your current needs. This makes the process of describing the infrastructure for a new project or even updating an existing one tedious and very prone to human error. There has not existed an official tool for describing and deploying CloudFormation stacks and AWS resources programmatically, and the community has turned to third-party tools like [troposphere](https://github.com/cloudtools/troposphere) in order to get benefits from a high level language like Python, but it does come with its own issues, like being behind on CloudFormation-supported services, updates, and some inconsistency in parameter naming.

That was the situation until now, that AWS releases its [CDK](https://aws.amazon.com/cdk/), or Cloud Development Kit.

> AWS CDK gives you the expressive power of programming languages for defining infrastructure. Familiar features such as objects, loops, and conditions accelerate your development process. You can also use AWS CDK with your integrated development environment (IDE) to take advantage of existing productivity tools and testing frameworks.

As of August 2019, languages supported are TypeScript, Python, Java (developer preview), and .NET (developer preview).

Positive
: This workshop will be based off the TypeScript libraries.

This workshop aims to showcase some of the features that makes the CDK unique (such as *constructs* and *aspects*) and to prove how they can solve some common challenges, such as corporate compliance, collaboration in development, reusability of templates, testing, and automated CI/CD processes.

## Prerequisites
Duration: 5
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html)
- AWS Account and User with appropiate rights
- [Node.js (>= 8.12.0)](https://nodejs.org)
- [AWS CDK Toolkit](https://github.com/aws/aws-cdk)

## CDK concepts
### Constructs
### Aspects
Duration: 10

## Importing and using an existing Construct
Duration: 15

## Creating our first Construct
