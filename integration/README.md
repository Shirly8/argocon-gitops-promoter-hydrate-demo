# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1c805c61f137c9a5a3885f7dfdd76515b186940f
kustomize build ./user-configuration/staging/integration
```
