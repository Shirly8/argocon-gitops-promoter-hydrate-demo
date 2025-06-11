
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a879e7233eb695c8dfe8796e467dfa0a84edad52
kustomize build ./user-configuration/staging/integration
```