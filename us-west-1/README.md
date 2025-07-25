# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b8ef6c491e6ab1596b31cac812d05baf3e2a2c51
kustomize build ./user-configuration/production/us-west-1
```
