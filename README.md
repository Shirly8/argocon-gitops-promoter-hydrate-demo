
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8f0950c8d1ce50b9fb2892a9e45b0d9a85845b58
kustomize build ./user-configuration/development
```