# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e7475a84b843eb277182adbc32583feaf5f90018
kustomize build ./user-configuration/staging/integration
```
