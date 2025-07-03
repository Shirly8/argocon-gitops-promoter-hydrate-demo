# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ee3396aced4580319a6f9c1109b262d03047a4fd
kustomize build ./user-configuration/development
```
