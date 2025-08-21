# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2bf6ab015be2f0a21035f1eb2e6d97f7500ee83f
kustomize build ./user-configuration/staging/e2e
```
