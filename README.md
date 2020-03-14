# aws-ecs-demo
Demo project provisioning aws infrastructure to run an ECS container behind an ALB

#### 1) Creating core stack
```aws cloudformation create-stack --region eu-west-1 --stack-name spring-redis-chat --capabilities CAPABILITY_NAMED_IAM --template-body file://cloudformation/core.yml```
