# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 777812218336ecf83d2d3d0049c185af2647a7c7
kustomize build ./user-configuration/development
```
