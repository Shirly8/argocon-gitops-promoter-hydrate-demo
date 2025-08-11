# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 34241d7205054376c17b8abdde6efe2c52474e0d
kustomize build ./user-configuration/development
```
