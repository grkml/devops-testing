# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/grkml/devops-testing.git
# cd into the cloned directory
git checkout a86729f183a50b5c1cde249162594d5d68578fbf
kustomize build ./argocd/apps/kyverno/overlays/minikube --enable-helm
```
