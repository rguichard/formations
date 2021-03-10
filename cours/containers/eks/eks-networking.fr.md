# EKS : Networking

## EKS Networking : Concepts

- Configuration VPC
- CNI: Container Network Interface
- Load-balancers

## EKS Networking : VPC

## EKS Networking : Subnets

  - Subnets publics
    - Permettent d'exposer les Load Balancers
    - Accès au control plane
  - Subnets privés
    - Empêchent d'accéder directement aux Nodes
    - Isolation des ressources

## EKS Networking : Security groups

- Cluster security group
- Control plane security group
- Node security group

## EKS Networking : Cluster endpoint access

- Accès public
- Accès privé
- Accès hybride (public et privé)

## EKS Networking : CNIs

- amazon-vpc-cni-k8s
- calico

## EKS Networking : AWS CNI

  - CNI VPC-native
    - Permet d'attribuer des IPs AWS directement aux Pods
    - Limite de 30 pods par Node (defaut)
    - Max 250 pods par Node

## EKS Networking : Calico

## EKS Networking : Load balancers

AWS Load Balancer Controller

- Application Load Balancer via les `Ingress`
- Network Load Balancer via les `Service`

