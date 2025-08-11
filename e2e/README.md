# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 101245dd71f8daf9af29877724679ff01485b8b7
kustomize build ./user-configuration/staging/e2e
```
