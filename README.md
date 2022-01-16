# AWS SAM(Serverless Architecture Model) sample application using AWS Lambda and AWS API Gateway
### Build and Deploy SAM app
```
$ sam build
$ sam deploy --guided
```
### Run SAM in local(Docker)
#### Note: Docker should be installed and running
```
$ sam local start-api
```
### Delete CloudFormation Stack
```
$ aws cloudformation delete-stack --stack-name <stack_name> --region <aws_region>
```