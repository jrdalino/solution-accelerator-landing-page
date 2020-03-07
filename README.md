# myproject-landing-page

## Prerequisites
- https://github.com/jrdalino/myproject-prerequisites

## Architecture Diagram
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/public-cloud-architecture-diagram-AWS.png)


| Step 1 | Set up Terraform State Backend             | https://github.com/jrdalino/myproject-aws-tfstate-backend-terraform |
| Step 2 | Set up VPC & EKS Cluster                   | https://github.com/jrdalino/myproject-aws-eks-terraform |
| Step 3 | Set up Lambda to EKS                       | https://github.com/jrdalino/myproject-aws-lambda-deploy-ecr-to-eks-nodejs |
| Step 4 | Setup NoSQL Database for Customer Service  | https://github.com/jrdalino/myproject-aws-dynamodb-customer-service-terraform |
| Step 5 | Setup Back End Customer Service            | https://github.com/jrdalino/myproject-customer-service-python |
| Step 6 |Setup CI/CD for Customer Service            | https://github.com/jrdalino/myproject-aws-codepipeline-customer-service-terraform |
| Step 7 | Setup NoSQL Database for Account Service   | https://github.com/jrdalino/myproject-aws-dynamodb-account-service-terraform |
| Step 8 | Setup Back End Acccount Service            | https://github.com/jrdalino/myproject-account-service-python |
| Step 9 | Setup CI/CD for Account Service            | https://github.com/jrdalino/myproject-aws-codepipeline-account-service-terraform |
| Step 10 | Setup Cognito                             | https://github.com/jrdalino/myproject-aws-cognito-terraform |
| Step 11 | API Gateway and VPC Link                  | https://github.com/jrdalino/myproject-aws-apigateway-terraform |
| Step 12 | Setup Front End (React)                   | https://github.com/jrdalino/myproject-web-service-react |
| Step 13 | Setup CI/CD for Front End Web App         | https://github.com/jrdalino/myproject-web-service-codepipeline-terraform |

# Nice to haves
- https://github.com/jrdalino/myproject-aws-organizations-multi-account-hardening
- https://github.com/jrdalino/myproject-kubernetes-helm-install
- https://github.com/jrdalino/myproject-kubernetes-helm-sonarqube
- EKS Dashboard
- https://github.com/jrdalino/myproject-aws-eks-xray-java
- AWS WAF
- AWS CloudFront
- Route53

# Appendix
- Naming Convention: < projname >-< provider >-< service >-< language >
