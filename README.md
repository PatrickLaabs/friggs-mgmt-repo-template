# Friggs Mgmt-Cluster GitOps Repository

![Frigg-Overview](assets/Frigg_Overview.png)

## Entry:

`./frigg-mgmt-cluster/kustomization.yaml`

### app-deployments/

Hold ArgoCD Application deployment definitions for your management
cluster.
These Applications are opionionated, and used for best-practice production-ready
kubernetes clusters.

### namespaces/

Namespace creations, which will later be needed to seperate some applications and to be more 
fine-granular.