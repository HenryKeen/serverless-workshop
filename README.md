# serverless-workshop

Goal: To learn how to use AWS lambdas and the serverless framework to build and deploy an API in AWS.

## AWS Lambda
AWS Lambda is a service offered by Amazon Web Services that hosts a single function for you. This function can be triggered via other AWS services and will scale out automatically to keep up with the demand. The services is totally managed so there is no need to manage or provision servers.

Lambda support functions written in Node.js, Java, C#, Go and Python.

- [Amazon Lambda Docs](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)

## Serverless

- [https://serverless.com/](https://serverless.com/)

- [Github](https://github.com/serverless/serverless/)

- [Quick start](https://serverless.com/learn/quick-start/)


## 1. Get the code

Get the code.

## 2. Install serverless

```
npm install -g serverless
```

## 3. Create a function
```
sls create --template aws-csharp --path hello-world
```