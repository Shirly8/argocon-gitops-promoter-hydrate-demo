# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ac89cb4b57f601935f154e8a5a6632618cb4411b
kustomize build ./user-configuration/staging/e2e
```
