# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e7f59f6df7691b2408e36d7efef86ec239a6f2c8
kustomize build ./user-configuration/staging/e2e
```
