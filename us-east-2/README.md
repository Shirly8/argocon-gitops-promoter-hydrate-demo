# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 14b18993ee6b8b3703c64def2c276dbac1da8504
kustomize build ./user-configuration/production/us-east-2
```
