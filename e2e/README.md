# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 013e7aaf3f158f7a68d0fd5250b05796185bb7a4
kustomize build ./user-configuration/staging/e2e
```
