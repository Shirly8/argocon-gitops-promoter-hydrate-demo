# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e16d26ced3894f575e3aacbad7887ed416ad9460
kustomize build ./user-configuration/staging/integration
```
