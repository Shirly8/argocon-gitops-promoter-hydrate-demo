# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0d39a3c2d009acb3fc5d593f3359347e4c0b011e
kustomize build ./user-configuration/development/dev
```
