# EKS : Nodes

## EKS Nodes : Types of node

- Managed
- Self-managed
- Fargate

## EKS Nodes: Managed nodes

- Node groups et instances crées et configurées par AWS
- Type de capacité "On-demand" ou "Spot"
- Gestion via le node group

## EKS Nodes : Self-managed nodes

- Node group est crée et configuré par AWS
- Provisionnement des noeuds se fait manuellement
- Configuration plus fine des noeuds
- Les noeuds doivent être déclarés auprès des node groups

## EKS Nodes : Fargate

- Déploiement des Pods directement sur Fargate
- Paiement à l'utilisation des ressources (vCPU, RAM)
- Administration via des Profiles Fargates

