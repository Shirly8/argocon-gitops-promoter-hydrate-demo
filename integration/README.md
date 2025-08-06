# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0485e21c0aacd441b5a0b5c6f547ca7d3d06e904
kustomize build ./user-configuration/staging/integration
```
