# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0ffdb784c479ccd24b57e9dc4f149d8952367d00
kustomize build ./user-configuration/staging/integration
```
