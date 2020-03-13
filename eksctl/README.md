# eksctl

## Creating a cluster:

Use the below command to create an EKS cluster and Worker Nodes
```
eksctl create cluster --version 1.14 --node-type t3.medium --name eks
```
## Customization 
Cluster can also be customized by using a config file, by running:
```
eksctl create cluster -f cluster.yaml
```
**cluster.yaml** in this directory contains customization with:
- SSH access
