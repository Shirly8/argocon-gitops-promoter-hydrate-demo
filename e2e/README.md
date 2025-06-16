# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ad617d43921a1be126c366057fe8f1f139deaf74
kustomize build ./user-configuration/staging/e2e
```
