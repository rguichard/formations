# EKS : Deployment

## EKS Deployment : Tools

## EKS Deployment : eksctl

- CLI officiel pour EKS
- Permet d'administrer les clusters EKS via une interface unique
- Configuration des addons EKS
- Bootstrapping GitOps - Flux

## EKS Deployment : CloudFormation

- Service d'IaC d'AWS
- Template disponible de QuickStart pour EKS

## EKS Deployment : Terraform

  - Terraform est un outil CLI pour IaC
  - Différents modules permettent de mettre en place des clusters EKS
    - `terraform-aws-modules/eks/aws/`
    - `cloudposse/eks-cluster/aws/`
  - Exemple d'utilisation dans `particuleio/teks`

## EKS Deployment : AWS CDK

- Cloud Development Kit
- Outil d'IaC d'AWS
- Permet de générer des templates CloudFormation via du code

## EKS Deployment : Pulumi

- IaC cloud-agnostic
- Système de components

