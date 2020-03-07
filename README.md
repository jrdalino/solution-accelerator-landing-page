# myproject-landing-page

## Prerequisites
- https://github.com/jrdalino/myproject-prerequisites

## Phase 1: Discover

## Phase 2: Prototype

## Phase 3: Pilot / MVP

### Architecture Diagram
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/public-cloud-architecture-diagram-AWS.png)

### Steps
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Set up Terraform State Backend             | https://github.com/jrdalino/myproject-aws-tfstate-backend-terraform |
| 2 | Set up VPC & EKS Cluster                   | https://github.com/jrdalino/myproject-aws-eks-terraform |
| 3 | Set up Lambda to EKS                       | https://github.com/jrdalino/myproject-aws-lambda-deploy-ecr-to-eks-nodejs |
| 4 | Setup NoSQL Database for Customer Service  | https://github.com/jrdalino/myproject-aws-dynamodb-customer-service-terraform |
| 5 | Setup Back End Customer Service            | https://github.com/jrdalino/myproject-customer-service-python |
| 6 |Setup CI/CD for Customer Service            | https://github.com/jrdalino/myproject-aws-codepipeline-customer-service-terraform |
| 7 | Setup NoSQL Database for Account Service   | https://github.com/jrdalino/myproject-aws-dynamodb-account-service-terraform |
| 8 | Setup Back End Acccount Service            | https://github.com/jrdalino/myproject-account-service-python |
| 9 | Setup CI/CD for Account Service            | https://github.com/jrdalino/myproject-aws-codepipeline-account-service-terraform |
| 10 | Setup Cognito                             | https://github.com/jrdalino/myproject-aws-cognito-terraform |
| 11 | API Gateway and VPC Link                  | https://github.com/jrdalino/myproject-aws-apigateway-terraform |
| 12 | Setup Front End (React)                   | https://github.com/jrdalino/myproject-web-service-react |
| 13 | Setup CI/CD for Front End Web App         | https://github.com/jrdalino/myproject-web-service-codepipeline-terraform |

### Notes
- Naming Convention: < project >-< provider >-< service >-< language >

## Phase 4: Scale
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS Account Hardening                      | https://github.com/jrdalino/myproject-aws-organizations-multi-account-hardening | 
| 2 | Helm Install                               | https://github.com/jrdalino/myproject-kubernetes-helm-install |
| 3 | Sonarqube Setup                            | https://github.com/jrdalino/myproject-kubernetes-helm-sonarqube |
| 4 | EKS Dashboard                              | Add URL here |
| 5 | AWS XRay                                   | https://github.com/jrdalino/myproject-aws-eks-xray-java |
| 6 | AWS KMS                                    | Add URL here |
| 7 | AWS WAF                                    | Add URL here |
| 8 | AWS CloudFront                             | Add URL here |
| 9 | AWS Route 53                               | Add URL here |
