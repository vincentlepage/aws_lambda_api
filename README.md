# aws_lambda_api

The goals of this project is to provide the basic components to deploy a scalable, serverless backend infrastructure for Mobile or Web application.

The main architectural choice made:
- Infrastructure as code, using Terraform. The present code properly executed will build the infrastructure
- serverless infrastructure: leveraging AWS Lambda, with Python backend
- AWS API gateway

This code does not provide actual usefull backend code, but just dummy examples.

## Howto/Install

Obviously you need an AWS account.

You can enter your AWS access and secret Keys in the variables.tf file to be generated from the template.

Dependencies: you need to have:
- Terraform installed
- Python 3.6

## License

This software is provided under the Apache 2.0 license.
See License.md for details.
