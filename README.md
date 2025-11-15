# AWS_DevOps_Stack

## Terminal Dev Commands

```
git add -A
git commit -m "your commit message here"
git checkout -b dev
git push -u origin dev
```


# DevOps Full Stack Practice Repository

## Intended Repository Structure

AWS_DevOps_Stack/
├── README.md
├── .gitignore
│
├── 01-infrastructure/
│   ├── terraform/
│   │   ├── aws/
│   │   │   ├── ec2/
│   │   │   ├── rds-aurora/
│   │   │   ├── s3/
│   │   │   ├── iam/
│   │   │   └── README.md
│   │   ├── oci/
│   │   └── README.md
│   ├── ansible/
│   │   ├── playbooks/
│   │   ├── roles/
│   │   ├── inventory/
│   │   └── README.md
│   └── README.md
│
├── 02-containerization/
│   ├── docker/
│   │   ├── sample-apps/
│   │   ├── multi-stage-builds/
│   │   └── README.md
│   ├── kubernetes/
│   │   ├── manifests/
│   │   ├── deployments/
│   │   ├── services/
│   │   ├── configmaps/
│   │   └── README.md
│   ├── helm/
│   │   ├── charts/
│   │   ├── values/
│   │   └── README.md
│   └── README.md
│
├── 03-cloud-platforms/
│   ├── aws/
│   │   ├── eks/
│   │   │   ├── cluster-setup/
│   │   │   ├── node-groups/
│   │   │   └── README.md
│   │   ├── ec2/
│   │   ├── rds/
│   │   ├── s3/
│   │   └── README.md
│   └── README.md
│
├── 04-cicd/
│   ├── github-actions/
│   │   ├── workflows/
│   │   ├── reusable-workflows/
│   │   ├── composite-actions/
│   │   └── README.md
│   ├── jenkins/
│   │   └── README.md
│   └── README.md
│
├── 05-monitoring/
│   ├── prometheus/
│   │   ├── configs/
│   │   ├── alerts/
│   │   └── README.md
│   ├── grafana/
│   │   ├── dashboards/
│   │   ├── datasources/
│   │   └── README.md
│   ├── loki/
│   │   ├── configs/
│   │   └── README.md
│   └── README.md
│
├── 06-projects/
│   ├── project-01-simple-webapp/
│   ├── project-02-microservices/
│   ├── project-03-full-stack/
│   └── README.md
│
└── docs/
    ├── architecture/
    ├── best-practices/
    └── troubleshooting/


## Recommended Public GitHub Repositories

### Infrastructure as Code
- **Terraform AWS**: https://github.com/terraform-aws-modules
- **Terraform Best Practices**: https://github.com/antonbabenko/terraform-best-practices
- **Ansible Examples**: https://github.com/ansible/ansible-examples

### Kubernetes & Container Orchestration
- **Kubernetes Examples**: https://github.com/kubernetes/examples
- **EKS Blueprints**: https://github.com/aws-ia/terraform-aws-eks-blueprints
- **Helm Charts**: https://github.com/helm/charts

### CI/CD
- **GitHub Actions Examples**: https://github.com/actions/starter-workflows
- **Awesome CI/CD**: https://github.com/cicdops/awesome-ciandcd

### Monitoring
- **Prometheus Examples**: https://github.com/prometheus/prometheus
- **Grafana Dashboards**: https://github.com/grafana/grafana
- **Loki Examples**: https://github.com/grafana/loki

### Full Stack Projects
- **DevOps Exercises**: https://github.com/bregman-arie/devops-exercises
- **DevOps Roadmap**: https://github.com/milanm/DevOps-Roadmap
- **Awesome DevOps**: https://github.com/awesome-soft/awesome-devops

## Practice Project Ideas per Directory

### 01-infrastructure/terraform/aws/ec2/
**Project**: Deploy auto-scaling web application
- Create VPC with public/private subnets
- Launch EC2 instances with auto-scaling
- Configure security groups and load balancer

### 02-containerization/kubernetes/
**Project**: Deploy microservices application
- Create deployments for frontend/backend
- Set up services and ingress
- Implement ConfigMaps and Secrets

### 04-cicd/github-actions/
**Project**: Complete CI/CD pipeline
- Build and test application
- Build Docker images
- Deploy to Kubernetes cluster

### 05-monitoring/
**Project**: Full observability stack
- Deploy Prometheus for metrics
- Configure Grafana dashboards
- Set up Loki for log aggregation
