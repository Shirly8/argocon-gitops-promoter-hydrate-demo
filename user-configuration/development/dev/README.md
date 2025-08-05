# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4b99b65405c7ba5897be3cdc92aeb84fd333d7ed
kustomize build ./user-configuration/development
```
