# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 14bb0d80d6aa060636b7cc4c82fcb1543e5dc71e
kustomize build ./user-configuration/staging/e2e
```
