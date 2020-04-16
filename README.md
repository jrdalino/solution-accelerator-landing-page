# Solution Accelerator Home

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

### Minimum Viable Pilot - Infra
- Infra Architecture Diagram: https://www.draw.io/#G1I1q3XWw3KAdFl1bfwG3AbW_tR6GKMXsB
- TODO: Service Mesh (App Mesh/Istio) and Service Discovery (Cloud Map)
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/public-cloud-architecture-diagram-AWS.png)

| Step | Description | URL | Status |
| ---- | ----------- | --- | ------ |
| 1 | Terraform State Backend   | https://github.com/jrdalino/aws-tfstate-backend-terraform | Done |
| 2 | VPC & EKS Cluster         | https://github.com/jrdalino/aws-vpc-terraform & https://github.com/jrdalino/aws-eks-terraform | Done |
| 3 | Lambda to EKS             | https://github.com/jrdalino/aws-lambda-deploy-ecr-to-eks-nodejs-terraform | Done |
| 4 | Cognito Identity & AuthN  | https://github.com/jrdalino/aws-cognito-terraform & https://github.com/jrdalino/myproject-consumer-web-amazon-cognito | Done |
| 5 | API Gateway and VPC Link  | https://github.com/jrdalino/aws-apigateway-terraform & https://github.com/jrdalino/amazon-api-gateway | Done |

### Minimum Viable Pilot - Microservices
- Application Architecture Diagram: https://app.diagrams.net/#G1MloaDlg1IMQL7WkI3KbIilyPGtFN3iJV
![Image description](https://github.com/jrdalino/myproject-landing-page/blob/master/application-architecture-diagram.png)

| Step | Description | URL | Status |
| ---- | ----------- | --- | ------ |
| 1 | Front End Webapp CI/CD    | https://github.com/jrdalino/myproject-aws-codepipeline-webapp-service-terraform | Done |
| 2 | Front End Webapp (React)  | https://github.com/jrdalino/myproject-web-service-react | Ongoing |
| 3 | Customer Service NoSQL DB | https://github.com/jrdalino/myproject-aws-dynamodb-customer-service-terraform | Done |
| 4 | Customer Service CI/CD    | https://github.com/jrdalino/myproject-aws-codepipeline-customer-service-terraform | Done |
| 5 | Customer Service API      | https://github.com/jrdalino/myproject-customer-service-python | Done |
| 6 | Product Service NoSQL DB  | https://github.com/jrdalino/myproject-aws-dynamodb-product-service-terraform | None |
| 7 | Product Service CI/CD     | https://github.com/jrdalino/myproject-aws-codepipeline-product-service-terraform | None |
| 8 | Product Service API       | https://github.com/jrdalino/myproject-product-service-python | Done |

- Naming Convention: < project >-< provider >-< service >-< language >

## Phase 4: Scale
### Choose the Right Storage / Database Service
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS ECR                   | https://github.com/jrdalino/aws-ecr-terraform |
| 2 | AWS CodeCommit            | https://github.com/jrdalino/aws-codecommit-terraform |
| 3 | AWS S3                    | https://github.com/jrdalino/aws-s3-terraform |
| 4 | AWS Glacier               | Add URL here |
| 5 | AWS EFS                   | Add URL here |
| 6 | AWS RDS                   | Add URL here |
| 7 | AWS DynamoDB              | https://github.com/jrdalino/aws-dynamodb-terraform |
| 8 | AWS Neptune               | Add URL here |
| 9 | AWS Redshift              | Add URL here |
| 10 | AWS Elasticsearch        | Add URL here |
| 11 | AWS SQS                  | https://github.com/jrdalino/aws-sqs-terraform |

### Security and Governance
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Zero Trust Model          | https://github.com/jrdalino/zero-trust-model-notes |
| 2 | AWS Account Hardening     | https://github.com/jrdalino/aws-organizations-multi-account-hardening |
| 3 | AWS Cloudtrail            | https://github.com/jrdalino/aws-cloudtrail |
| 4 | AWS Delete Default VPC    | https://github.com/jrdalino/aws-delete-default-vpc |
| 5 | AWS Secrets, Parameters   | https://github.com/jrdalino/aws-secrets-manager |
| 6 | AWS Inspector             | Add URL here |
| 7 | AWS Macie                 | Add URL here |
| 8 | AWS Certificate Manager   | SSL/TLS using AWS Certificate Mgr https://github.com/jrdalino/aws-certificate-manager |
| 9 | AWS KMS                   | Add URL here |
| 10 | AWS WAF                  | Add URL here |
| 11 | AWS Firewall Manager     | Add URL here |
| 12 | AWS Artifact             | Add URL here |
| 13 | AWS Security Hub         | Add URL here |
| 14 | AWS Detective            | Add URL here |
| 15 | OWASP Top 10             | https://github.com/aws-samples/aws-waf-sample/blob/master/waf-owasp-top-10/owasp_10_base.yml |
| 16 | AWS GuardDuty            | https://github.com/jrdalino/aws-guardduty |
| 17 | Backend Static Testing w/ Sonarqube       | https://github.com/jrdalino/kubernetes-helm-sonarqube |
| 18 | Backend Dynamic Testing  | Container Scanning w/ Anchore Engine / Aqua Microscanner / Clair / Dagda / Twistlock |
| 19 | Frontend Static Testing  | https://www.npmjs.com/package/auditjs & https://retirejs.github.io/retire.js & https://www.owasp.org/index.php/OWASP_Dependency_Check |
| 20 | Frontend Dynamic Testing | https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project |
| 21 | Check for commited secrets on Git Repo    | https://github.com/awslabs/git-secrets & https://github.com/zricethezav/gitleaks |

### Reliability
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Install Grafana using Helm                 | https://github.com/jrdalino/install-grafana-using-helm |
| 2 | Deploy monitoring using Prometheus         | https://github.com/jrdalino/install-prometheus-using-helm |
| 3 | Instrumentation w/ AWS XRay, Zipkin, Opentracing | https://github.com/jrdalino/aws-eks-xray-java |
| 4 | Service Discovery w/ Consul, AWS CloudMap  | Add URL here | 
| 5 | Service Mesh w/ Istio or AWS Appmesh       | https://github.com/jrdalino/istio-notes |
| 6 | Alerting w/ AlertManager, PagerDuty, Slack | Add URL here | 
| 7 | Logging w/ ElastiSearch, Fluentd, Kibana   | https://github.com/jrdalino/elasticsearch-fluentd-kibana |

###  Performance Efficiency
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS CloudFront                             | Add URL here |
| 2 | AWS Route 53                               | Register/Transfer Domain Name using Route 53 for CloudFront CDN |
| 3 | RDS Read Replica                           | Add URL here |
| 4 | AWS DynamoDB DAX                           | Add URL here |
| 5 | AWS ElastiCache (Redis)                    | Add URL here |
| 6 | EKS Cluster AutoScaling                    | https://github.com/jrdalino/kubernetes-autoscaling |
| 7 | Kubernetes Horizontal Pod AutoScaler       | https://github.com/jrdalino/kubernetes-autoscaling |
| 8 | Kubernetes Liveness Probes                 | https://github.com/jrdalino/kubernetes-liveness-probes |
| 9 | Kubernetes Readiness Probes                | https://github.com/jrdalino/kubernetes-readiness-probes |
| 10 | AI Ops                                    | Predictive Autoscaling for Kubernetes w/ Prometheus + Amazon SageMaker |
| 11 | Load Testing w/ Locust JMeter             | Add URL here |

###  Cost Optimisation
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | Tagging Standards                          | https://aws.amazon.com/answers/account-management/aws-tagging-strategies/ |
| 2 | AWS Cost Explorer                          | https://github.com/jrdalino/aws-cost-explorer |
| 3 | AWS Budgets                                | https://github.com/jrdalino/aws-budgets |
| 4 | AWS Pricing Calculator                     | https://calculator.s3.amazonaws.com/index.html & https://calculator.aws/#/ |

###  Operational Excellence
#### Governance
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | AWS Organizations                          | Add URL here |
| 2 | AWS Cloudtrail                             | Add URL here |
| 3 | AWS AutoScaling                            | Add URL here |
| 4 | AWS Config                                 | Add URL here |
| 5 | AWS Trusted Advisor                        | https://github.com/jrdalino/aws-trusted-advisor |
| 6 | AWS Well Architected Review                | https://github.com/jrdalino/aws-well-architected-questions & https://ap-southeast-2.console.aws.amazon.com/wellarchitected/home?region=ap-southeast-2#/welcome | |
| 7 | AWS Infrastructure Event Management        | https://github.com/jrdalino/aws-infrastructure-event-management |
| 8 | CI/CD For IaaS                             | Add URL here |
| 9 | Helm Install                               | https://github.com/jrdalino/kubernetes-helm-install |
| 10 | CI/CD for IaaS                            | Cloudformation: https://github.com/aws-quickstart/quickstart-taskcat-ci & Terraform: https://dzone.com/articles/immutable-infrastructure-cicd-using-hashicorp-terr |

#### Observability
| Step | Description | URL |
| ---- | ----------- | --- |
| 1 | EKS Dashboard                              | https://github.com/jrdalino/aws-eks-dashboard-kubectl |
| 2 | AWS Cloudwatch (Observability: Metrics)    | Add URL here |
| 3 | AWS Cloudwatch (Observability: Logs)       | Add URL here |
| 4 | AWS X-Ray (Observability: Traces)          | https://github.com/jrdalino/aws-xray-python |
| 5 | AWS Service Health Dashboard               | https://status.aws.amazon.com/ |
| 6 | AWS Personal Health Dashboard              | https://phd.aws.amazon.com/phd/home#/dashboard/open-issues |
| 7 | AWS Health                                 | https://github.com/jrdalino/aws-health |

## Appendix
- Kubernetes: https://github.com/jrdalino/aws-eks-eksctl & https://github.com/jrdalino/azure-aks-azcli & https://github.com/jrdalino/kubernetes-cluster-build & https://github.com/jrdalino/single-master-kubernetes-cluster & https://github.com/jrdalino/multi-master-kubernetes-cluster-kops
- https://github.com/GoogleCloudPlatform/microservices-demo
- https://github.com/aws-samples/reinvent2018-dev303-code
