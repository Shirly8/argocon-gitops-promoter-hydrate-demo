# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4815f401a18d007adda9a2e3a3de71e8d9dd625a
kustomize build ./user-configuration/staging/e2e
```
