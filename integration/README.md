# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f789aebfc778b1474b6fb8fad86b6465b7b59881
kustomize build ./user-configuration/staging/integration
```
