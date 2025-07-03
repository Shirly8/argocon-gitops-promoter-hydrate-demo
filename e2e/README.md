# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2dbbf4651f9499ee001c163b1c9d9b8e467caec0
kustomize build ./user-configuration/staging/e2e
```
