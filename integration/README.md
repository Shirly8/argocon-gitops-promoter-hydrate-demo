# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ea1ffb1a46059f994245ef910f26a997b5eb9f0a
kustomize build ./user-configuration/staging/integration
```
