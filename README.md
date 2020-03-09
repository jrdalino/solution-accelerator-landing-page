# myproject-landing-page

## Prerequisites
- https://github.com/jrdalino/development-environment-setup

## Phase 1: Discover
- Business Model Canvas: https://docs.google.com/drawings/d/102mOZQmMxs0CslmNsPZ5KCNQwAIh9rh4baYgT0VWNAA/template/preview?usp=drive_web
- Functional
- Non Functional Requirements

## Phase 2: Prototype
- Storyboard
- Wireframes
- Mockups
- POC: https://github.com/jrdalino/aws-amplify-notes

## Phase 3: Pilot / MVP
- Business Metrics
- Service Levels
- Software Architecture: https://github.com/jrdalino/system-design-primer
- Infra Architecture Diagram: https://www.draw.io/#G1I1q3XWw3KAdFl1bfwG3AbW_tR6GKMXsB
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/public-cloud-architecture-diagram-AWS.png)

### Minimum Viable Pilot (MVP)
| Step | Description | URL | Status |
| ---- | ----------- | --- | ------ |
| 1 | Set up Terraform State Backend             | https://github.com/jrdalino/aws-tfstate-backend-terraform | Done |
| 2 | Set up VPC & EKS Cluster                   | https://github.com/jrdalino/aws-eks-terraform & https://github.com/jrdalino/aws-eks-eksctl & https://github.com/jrdalino/azure-aks-azcli & https://github.com/jrdalino/kubernetes-cluster-build & https://github.com/jrdalino/aws-vpc-terraform | Done |
| 3 | Set up Lambda to EKS                       | https://github.com/jrdalino/aws-lambda-deploy-ecr-to-eks-nodejs | For Checking |
| 4 | Setup NoSQL Database for Customer Service  | https://github.com/jrdalino/myproject-aws-dynamodb-customer-service-terraform | Done |
| 5 | Setup Back End Customer Service            | https://github.com/jrdalino/myproject-customer-service-python & https://github.com/jrdalino/backend-python-flask-restapi-calculator | Not Yet Started |
| 6 |Setup CI/CD for Customer Service            | https://github.com/jrdalino/myproject-aws-codepipeline-customer-service-terraform | For Checking |
| 7 | Setup NoSQL Database for Account Service   | https://github.com/jrdalino/myproject-aws-dynamodb-account-service-terraform | Not Yet Started |
| 8 | Setup Back End Acccount Service            | https://github.com/jrdalino/myproject-account-service-python | Not Yet Started |
| 9 | Setup CI/CD for Account Service            | https://github.com/jrdalino/myproject-aws-codepipeline-account-service-terraform | Not Yet Started |
| 10 | Setup Cognito                             | https://github.com/jrdalino/aws-cognito-terraform | For Checking |
| 11 | API Gateway and VPC Link                  | https://github.com/jrdalino/aws-apigateway-terraform | Ongoing |
| 12 | Setup Front End (React)                   | https://github.com/jrdalino/myproject-web-service-react | Not Yet Started |
| 13 | Setup CI/CD for Front End Web App         | https://github.com/jrdalino/myproject-web-service-codepipeline-terraform | Not Yet Started |

- Naming Convention: < project >-< provider >-< service >-< language >

## Phase 4: Scale
### Choose the Right Storage / Database Service
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS ECR                                    | https://github.com/jrdalino/aws-ecr-terraform |
| 2 | AWS CodeCommit                             | https://github.com/jrdalino/aws-codecommit-terraform |
| 3 | AWS S3                                     | https://github.com/jrdalino/aws-s3-terraform |
| 4 | AWS Glacier                                | Add URL here |
| 5 | AWS EFS                                    | Add URL here |
| 6 | AWS RDS                                    | Add URL here |
| 7 | AWS DynamoDB                               | https://github.com/jrdalino/aws-dynamodb-terraform |
| 8 | AWS DynamoDB DAX                           | Add URL here |
| 9 | AWS ElastiCache                            | Add URL here |
| 10 | AWS Neptune                               | Add URL here |
| 11 | AWS Redshift                              | Add URL here |
| 12 | AWS Elasticsearch                         | Add URL here |

### Security and Governance
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Zero Trust Model                           | https://github.com/jrdalino/zero-trust-model-notes |
| 2 | AWS Account Hardening                      | https://github.com/jrdalino/aws-organizations-multi-account-hardening |
| 3 | AWS Cloudtrail                             | https://github.com/jrdalino/aws-cloudtrail |
| 4 | AWS Delete Default VPC                     | https://github.com/jrdalino/aws-delete-default-vpc |
| 5 | AWS Secrets Manager                        | https://github.com/jrdalino/aws-secrets-manager |
| 6 | AWS Inspector                              | Add URL here |
| 7 | AWS Macie                                  | Add URL here |
| 8 | AWS Certificate Manager                    | https://github.com/jrdalino/aws-certificate-manager |
| 9 | AWS KMS                                    | Add URL here |
| 10 | AWS WAF                                   | Add URL here |
| 11 | AWS Firewall Manager                      | Add URL here |
| 12 | AWS Artifact                              | Add URL here |
| 13 | AWS Security Hub                          | Add URL here |
| 14 | AWS Detective                             | Add URL here |
| 15 | OWASP Top 10                              | https://github.com/aws-samples/aws-waf-sample/blob/master/waf-owasp-top-10/owasp_10_base.yml |
| 16 | AWS GuardDuty                             | https://github.com/jrdalino/aws-guardduty |
| 17 | Backend Static Testing w/ Sonarqube       | https://github.com/jrdalino/kubernetes-helm-sonarqube |
| 18 | Backend Dynamic Testing                   | Add URL here |
| 19 | Frontend Static Testing                   | https://www.npmjs.com/package/auditjs & https://retirejs.github.io/retire.js & https://www.owasp.org/index.php/OWASP_Dependency_Check |
| 20 | Frontend Dynamic Testing                  | https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project |

### Reliability
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS XRay                                   | https://github.com/jrdalino/aws-eks-xray-java |
| 2 | Istio                                      | https://github.com/jrdalino/istio-notes |

###  Performance Efficiency
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS CloudFront                             | Add URL here |
| 2 | AWS Route 53                               | Add URL here |

###  Cost Optimisation
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Tagging Standards                          | https://aws.amazon.com/answers/account-management/aws-tagging-strategies/ |
| 2 | AWS Cost Explorer                          | https://github.com/jrdalino/aws-cost-explorer |
| 3 | AWS Budgets                                | https://github.com/jrdalino/aws-budgets |
| 4 | AWS Pricing Calculator                     | https://calculator.s3.amazonaws.com/index.html & https://calculator.aws/#/ |


###  Operational Excellence
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS Organizations                          | Add URL here |
| 2 | AWS Cloudwatch                             | Add URL here |
| 3 | AWS AutoScaling                            | Add URL here |
| 4 | EKS Cluster AutoScaling                    | https://github.com/jrdalino/kubernetes-autoscaling |
| 5 | Kubernetes Horizontal Pod AutoScaler       | https://github.com/jrdalino/kubernetes-autoscaling |
| 6 | Kubernetes Liveness Probes                 | https://github.com/jrdalino/kubernetes-liveness-probes |
| 7 | Kubernetes Readiness Probes                | https://github.com/jrdalino/kubernetes-readiness-probes |
| 8 | AWS Config                                 | Add URL here |
| 9 | AWS Trusted Advisor                        | https://github.com/jrdalino/aws-trusted-advisor |
| 10 | AWS Well Architected Review                | https://github.com/jrdalino/aws-well-architected-questions & https://ap-southeast-2.console.aws.amazon.com/wellarchitected/home?region=ap-southeast-2#/welcome |
| 11 | AWS Service Health Dashboard               | https://status.aws.amazon.com/ |
| 12 | AWS Personal Health Dashboard             | https://phd.aws.amazon.com/phd/home#/dashboard/open-issues |
| 13 | AWS Health                                | https://github.com/jrdalino/aws-health |
| 14 | AWS Infrastructure Event Management       | https://github.com/jrdalino/aws-infrastructure-event-management |
| 15 | CI/CD For IaaS                            | Add URL here |
| 16 | Helm Install                              | https://github.com/jrdalino/kubernetes-helm-install |
| 17 | EKS Dashboard                             | https://github.com/jrdalino/aws-eks-dashboard-kubectl |
| 18 | Install Grafana using Helm                | https://github.com/jrdalino/install-grafana-using-helm |
| 19 | Install Prometheus using Helm             | https://github.com/jrdalino/install-prometheus-using-helm |
