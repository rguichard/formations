# EKS : Storage

## EKS Storage : Concepts

- Classes de stockage
- Les classes "In-tree"
- Les CSI drivers

## EKS Storage : Classes

## EKS Storage : In-tree plugin

Plugin `AWS EBS` disponible nativement dans Kubernetes.

- Type de volume SSD: `io1`, `gp2`
- Type de volume HDD: `sc1`, `st1`

## EKS Storage : Out-of-tree plugins (CSI)

- EBS CSI driver: Stockage via blocks
- EFS CSI driver: Stockage via NFS

## EKS Storage : EBS CSI driver

  - Utilise les memes ressources que le plugin In-Tree pour EBS
  - Offre des fonctionnalites additionnelles
    - Provisionnement de Volume "Block"
    - Snapshot de Volume
    - Redimensionnement de Volume

## EKS Storage : EFS CSI driver

  - Permet d'utiliser la solution NFS d'AWS (EFS)
  - Features
    - Chiffrement lors du transfert de donnees (via TLS)
    - Redimensionnement de volume

