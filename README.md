# Cashflow infrastructure 

## 1. Cloudformation

### 1.1 Create stack

Create stack in the aws cloud
```bash
aws cloudformation create-stack --stack-name cashflow-stack --template-body file://ecs-cloudformation.yml --capabilities CAPABILITY_NAMED_IAM
```
### 1.2 Update stack
Update stack resources in the aws cloud
```bash
aws cloudformation update-stack --stack-name cashflow-stack --template-body file://ecs-cloudformation.yml --capabilities CAPABILITY_NAMED_IAM
```