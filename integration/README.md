# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fb44e3e1b4cc3fe407edb22c56c70aef6217f01a
kustomize build ./user-configuration/staging/integration
```
