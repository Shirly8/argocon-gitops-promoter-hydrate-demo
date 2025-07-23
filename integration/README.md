# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 97334f6ece46aa69820fc383038f30475908dff3
kustomize build ./user-configuration/staging/integration
```
