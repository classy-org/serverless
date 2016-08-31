<!--
title: Serverless AWS Documentation
layout: Page
-->

# Serverless AWS Documentation

Check out the [Getting started guide](../../getting-started) and the [CLI reference](../../cli-reference) for an introduction to Serverless.

# [Setup and configuration](./setup.md)

Please follow these [setup instructions](./01-setup.md) to start using AWS Lambda and serverless together

## About AWS Lambda

Learn more about the programming model of lambda functions http://docs.aws.amazon.com/lambda/latest/dg/programming-model-v2.html

## General Configuration

* [Configuring IAM resources](02-iam.md)
* [VPC configuration](03-vpc.md)

## AWS events

* [API Gateway](./events/01-api-gateway.md)
* [S3](./events/02-s3.md)
* [Schedule](./events/03-schedule.md)
* [SNS](./events/04-sns.md)
* [Kinesis Streams](./events/05-kinesis-streams.md)
* [Dynamodb Streams](./events/06-dynamodb-streams.md)

## [Examples](./examples)

See the examples folder for all AWS serverless examples

- [hello-world](./examples/hello-world)
- [using-external-libraries](./examples/using-external-libraries)
- [web-api](./examples/web-api)

To add examples, fork this repo and submit a pull request
