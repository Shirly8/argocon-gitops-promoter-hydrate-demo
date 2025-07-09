# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 379ed57b753f3f309bcb840074409a4008e00e68
kustomize build ./user-configuration/staging/e2e
```
