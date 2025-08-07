# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d4cebe64ba991a3a2d3d5c021c65b98bc3cf3656
kustomize build ./user-configuration/staging/e2e
```
