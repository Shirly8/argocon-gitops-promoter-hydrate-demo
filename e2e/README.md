# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1e4a07dc6170e71603c126f7b335364c09c9493a
kustomize build ./user-configuration/staging/e2e
```
