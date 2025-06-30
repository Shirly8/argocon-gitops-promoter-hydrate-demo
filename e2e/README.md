# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout eb40dc4590b43fa244f7f55ede7bf169198ff997
kustomize build ./user-configuration/staging/e2e
```
