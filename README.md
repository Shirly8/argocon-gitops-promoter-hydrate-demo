# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 338d4e6d10943cf011ff2921517cd1ff96ff4074
kustomize build ./user-configuration/development
```
