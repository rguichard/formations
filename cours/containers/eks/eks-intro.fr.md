# Elastic Kubernetes Service (EKS)

## EKS: Presentation

  - Solution de Cluster Kubernetes managé par AWS
  - Flexible et configurable, possibilité de scale facilement
  - Intégration avec les services AWS (VPC, stockage, authentification)
  - Différents types de noeuds (managed, self-managed, fargate)

## EKS: Why and for whom ?

  - Facilite l'adoption de Kubernetes
  - Permet de tirer profit du modèle de responsabilité partagée AWS (SLA)
  - Mises à jours automatiques de securités
  - Provisionnement et mise à l'echelle via AWS

## EKS configuration: Setup

  - Amazon EKS pour configurer EKS dans le cloud AWS
  - Amazon EKS Distro pour configurer EKS dans un cloud privé
  - Amazon EKS Anywhere pour les ressources dans des clouds privés (2021)

## EKS configuration: Installation

  - Via la console AWS
  - Via Cloudformation
  - Via `eksctl`
  - Via des outils IaC (terraform, ansible)

## EKS integration: AWS Services

  - Intégrations multiples dans une infrastructure existante
    - Logs vers AWS CloudTrail
    - Authentification via IAM
    - CNI vpc-native

