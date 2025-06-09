
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 854aec1d36c14b2f76fb9bd0b8f51ed8a16d1e00
kustomize build ./user-configuration/staging/integration
```