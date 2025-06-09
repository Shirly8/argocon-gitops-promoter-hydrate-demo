
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ccba8428ecb4c8f116813202c03d31f069ebdb16
kustomize build ./user-configuration/development
```