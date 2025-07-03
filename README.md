# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 36dc78880a78d2ebc407f6862f8cc96fd760b1a6
kustomize build ./user-configuration/development
```
