### Install Kyverno
```
helm repo add kyverno https://kyverno.github.io/kyverno/
helm repo update 
helm install kyverno --namespace kyverno kyverno/kyverno --create-namespace
```
