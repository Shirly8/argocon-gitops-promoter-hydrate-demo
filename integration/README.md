# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5bdfe67c121746eb91a064adbcd107de8b66ca5a
kustomize build ./user-configuration/staging/integration
```
