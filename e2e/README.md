# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c8260214175c12ee887fd70f552b0812c98dc117
kustomize build ./user-configuration/staging/e2e
```
