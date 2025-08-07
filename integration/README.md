# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4fb794049c8a21cbe5b680d46d1163d10c80f303
kustomize build ./user-configuration/staging/integration
```
