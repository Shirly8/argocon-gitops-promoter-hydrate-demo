
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4c461f4eee763f2085ba80c56b1bf413c162d73f
kustomize build ./user-configuration/staging/integration
```