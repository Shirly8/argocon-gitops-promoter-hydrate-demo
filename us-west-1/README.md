
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a857e27a8822df8c1b279cdfec4a6d8cecb51a2c
kustomize build ./user-configuration/production/us-west-1
```