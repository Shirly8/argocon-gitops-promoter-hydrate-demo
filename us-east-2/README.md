# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1d1dede19de3c1d3d5a9decce85aa20326d2eac5
kustomize build ./user-configuration/production/us-east-2
```
