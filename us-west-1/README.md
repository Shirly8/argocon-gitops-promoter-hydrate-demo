# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 142fefc268e2d648e3e2ddc6c0a095f5a4c4d305
kustomize build ./user-configuration/production/us-west-1
```
