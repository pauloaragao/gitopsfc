# Gitops 
Ferramentas utilizadas.

## Kind K8s Windows
https://kind.sigs.k8s.io/docs/user/quick-start/

`kind create cluster --name gitopsfc`

## ArgoCD
https://argoproj.github.io/cd/

`kubectl port-forward svc/argocd-server -n argocd 8080:443`
