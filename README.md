# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6258303f96382629af23f5b72930dee2cdfcd64a
kustomize build ./user-configuration/development
```
