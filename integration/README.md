
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ce3a30b8ccd759a0170b32cd1b7eb1986b393582
kustomize build ./user-configuration/staging/integration
```