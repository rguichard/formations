# EKS : AWS Integrations

## EKS AWS Integrations : Components

  - Gestion de l'authentification / permissions
  - Stockage d'Images
  - Intégration network
    - Création de Load Balancers
    - aws-vpc-cni
  - Monitoring
    - Logs
    - Metrics
  - EKS Helm Charts

## EKS AWS Integrations : IAM

`aws-iam-authenticator` permet d'utiliser les rôles / utilisateurs IAM
comme source de vérité pour l'authentification.

## EKS AWS Integrations : ECR

Il est possible d'autoriser un Cluster EKS à utiliser un ECR sans
authentification via un `Secret` en accordant les permissions ci-dessous
aux worker nodes.

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Action": [
                "ecr:BatchCheckLayerAvailability",
                "ecr:BatchGetImage",
                "ecr:GetDownloadUrlForLayer",
                "ecr:GetAuthorizationToken"
            ],
            "Resource": "*"
        }
    ]
}
```

## EKS AWS Integrations : Networking

- CNI VPC-native: `aws-vpc-cni`
- Création dynamique de Load Balancer via le Load Balancer Controller

## EKS AWS Integrations : Monitoring

- Collection de metrics du Cluster via Container Insights for Kubernetes
- Collection des logs vers CloudWatch Logs

### EKS AWS Monitoring : Metrics

### EKS AWS Monitoring : Logs

## EKS AWS Integrations : EKS Helm Charts

De nombreuses intégrations sont disponibles via des Charts Helm (`aws.github.io/eks-charts`).

- Intégrations avec le service AWS App Mesh
- Déploiement d'agent de collection de metrics CloudWatch
- Gestion des network policies (calico, aws-vpc-cni)

