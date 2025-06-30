# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 76d3c566a05c5d5db6bcd379fa34a1b27bff76d1
kustomize build ./user-configuration/development
```
