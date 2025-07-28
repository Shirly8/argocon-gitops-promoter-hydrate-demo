# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f0aec86dbf9ba8ac6de219fef3ced6df948fe382
kustomize build ./user-configuration/staging/e2e
```
