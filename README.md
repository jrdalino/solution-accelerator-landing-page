# myproject-landing-page

## Prerequisites
- https://github.com/jrdalino/myproject-prerequisites

## Phase 1: Discover
- Business Model Canvas: https://docs.google.com/drawings/d/102mOZQmMxs0CslmNsPZ5KCNQwAIh9rh4baYgT0VWNAA/template/preview?usp=drive_web

## Phase 2: Prototype
- Storyboard
- Wireframes
- Mockups
- POC: https://github.com/jrdalino/aws-amplify-notes

## Phase 3: Pilot / MVP
- Business Metrics
- Service Levels
- Software Architecture: https://github.com/jrdalino/system-design-primer
- Infra Architecture Diagram:
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/public-cloud-architecture-diagram-AWS.png)

### Steps
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Set up Terraform State Backend             | https://github.com/jrdalino/myproject-aws-tfstate-backend-terraform |
| 2 | Set up VPC & EKS Cluster                   | https://github.com/jrdalino/myproject-aws-eks-terraform & https://github.com/jrdalino/myproject-aws-eks-eksctl |
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

- Naming Convention: < project >-< provider >-< service >-< language >

## Phase 4: Scale
### Security and Governance
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS Account Hardening                      | https://github.com/jrdalino/myproject-aws-organizations-multi-account-hardening | 
| 2 | AWS KMS                                    | Add URL here |
| 3 | AWS Secrets Manager                        | https://github.com/jrdalino/aws-secrets-manager |
| 4 | AWS Certificate Manager                    | https://github.com/jrdalino/aws-certificate-manager |
| 4 | AWS WAF                                    | Add URL here |
| 5 | Zero Trust Model                           | https://github.com/jrdalino/zero-trust-model-notes |
| 6 | OWASP Top 10                               | https://github.com/aws-samples/aws-waf-sample/blob/master/waf-owasp-top-10/owasp_10_base.yml |
| 7 | Backend Static Testing w/ Sonarqube        | https://github.com/jrdalino/myproject-kubernetes-helm-sonarqube |
| 8 | Backend Dynamic Testing                    | Add URL here |
| 9 | Frontend Static Testing                    | https://www.npmjs.com/package/auditjs & https://retirejs.github.io/retire.js & https://www.owasp.org/index.php/OWASP_Dependency_Check |
| 10 | Frontend Dynamic Testing                   | https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project |

### Reliability
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS XRay                                   | https://github.com/jrdalino/myproject-aws-eks-xray-java |

###  Peformance Efficiency
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS CloudFront                             | Add URL here |
| 2 | AWS DynamoDB DAX                           | Add URL here |
| 3 | AWS Elasticsearch                          | Add URL here |
| 4 | AWS RDS                                    | Add URL here |
| 5 | AWS ElastiCache                            | Add URL here |

###  Cost Optimisation
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Tagging Standards                          | https://aws.amazon.com/answers/account-management/aws-tagging-strategies/ |
| 2 | AWS Cost Explorer                          | https://github.com/jrdalino/myproject-aws-cost-explorer |


###  Operational Excellience
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS Route 53                               | Add URL here |
| 2 | Helm Install                               | https://github.com/jrdalino/myproject-kubernetes-helm-install |
| 3 | EKS Dashboard                              | https://github.com/jrdalino/myproject-aws-eks-dashboard-kubectl |
| 4 | CI/CD For IaaS                             | Add URL here |
