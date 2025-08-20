# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ffe420106ec4cd348bd1bb22ca3128612d0f5521
kustomize build ./user-configuration/development
```
