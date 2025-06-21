# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4fce42fc65cee2b624d907ccbca82d752045be44
kustomize build ./user-configuration/staging/integration
```
