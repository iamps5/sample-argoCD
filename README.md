This repo gives you a quick overview of argoCD.

Make sure you have argoCD installed in your k8s cluster. Once installed just define & apply the application CRD in your cluster.
Then, ArgoCD will apply all the resources YAML files at the path defined in the application CRD. Also, it will always keep monitoring the repo and as soon as any defination changes, it will apply those changes in your cluster. 

Your repo will be final source of truth for argoCD and in GitOps Manner it will keep in sync your cluster with your repo
