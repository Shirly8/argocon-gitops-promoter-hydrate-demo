# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 47398abde25c288c57c25d2806c8d4b580e79a69
kustomize build ./user-configuration/staging/e2e
```
