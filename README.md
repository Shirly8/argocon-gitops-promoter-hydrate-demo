
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9c02c60408bdd3d4bd5d36a430f97fb32fee9d9c
kustomize build ./user-configuration/development
```