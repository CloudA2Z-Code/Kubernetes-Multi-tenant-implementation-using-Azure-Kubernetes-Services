# Kubernetes-Azure-Kubernetes-Services-Multi-tenant-implementation
This repository has files to implement a end to end kubernetes(AKS) multi-tenant architecture in your organisation(Azure,Azure or GCP), where each tenant(teams or applications) will be provisioned with 'Namespace' basically a logical separation in k8s which helps in attaining multi-tenancy easily.

Implementation:
==============
1) Creation of Server principal and Client Principal in AWS IAM or Azure Azure Active Directory(AAD).
2) Spinning up an RBAC enabled Kubernetes Cluster using Azure CLI Command.
3) Prepare Yamls for each tenants(Role and RoleBinding).
4) Define add-on Yamls(resource quota, limit range).
5) DevOps integaraton for deploying applications into provisioned Kubernetes(AKS) cluster.
