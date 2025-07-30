# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 196e966171af53531c5789f86fa6e4a9354357aa
kustomize build ./user-configuration/staging/e2e
```
