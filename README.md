# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3d9ae3ea4cd18d2fad126fbad4ae3e3f9d70d9ea
kustomize build ./user-configuration/development
```
