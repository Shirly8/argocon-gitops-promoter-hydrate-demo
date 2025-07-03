# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f715d547e60cbc3c994ba311a2016301b37a0b96
kustomize build ./user-configuration/staging/e2e
```
