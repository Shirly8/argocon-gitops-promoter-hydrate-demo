# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 30843a2a71ecf6dba6041074be938e7bb453093e
kustomize build ./user-configuration/staging/integration
```
