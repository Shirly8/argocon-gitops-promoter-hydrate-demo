# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8d0f57a61447d6e37da036abe0802a4c0818acb9
kustomize build ./user-configuration/development
```
