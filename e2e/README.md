# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a6e2c9e14016165939c071606ec574f491cc6084
kustomize build ./user-configuration/staging/e2e
```
