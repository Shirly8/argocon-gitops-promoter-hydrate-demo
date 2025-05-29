
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7df4e1579b6b7b49c4758622657e943f9c49bd73
kustomize build ./user-configuration/production/us-east-2
```