# Cloud Resume Challenge 2.0

## Introduction
This is my second CRC, the 1st - [Cloud Resume Challenge](https://github.com/Thab310/cloud-resume-challenge) was created using Cloudformation and python. On this one I am challenging myself to create it using terraform and Go.

Special shout out to [Forrest Brazeal](https://x.com/forrestbrazeal) the creater of the [CRC](https://cloudresumechallenge.dev/).

## Improvements
* I used terraform for IAC instead of of AWS (serverless application model) SAM because it cloud agnostic.
* I used AWS Lambda function url instead of API Gateway in order to reduce complexity and optimise the application by getting rid of the addition network hop. :) less is more
* added terraform tests using terratest
* I decided to split the app into 2 different repos ( Backend, Frontend) each has it's own CI/CD pipeline
* S3 bucket is no longer public
* I decided to go for golang for my lambda instead of python because it is more performant

## Prequesites
* Buy a domain name from [Amazon Route53](https://aws.amazon.com/route53/). You could also use any other domain name that you already have.
* Install:
    * Terraform
    * AWS cli
    * Go
    * git

## Diagrams

### Architecture
### CI/CD Flows

