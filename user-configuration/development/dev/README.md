# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 26a60b3e015750ee2aa4da10ccb6c6de5c4c1d53
kustomize build ./user-configuration/development
```
