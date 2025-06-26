# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c3a00ea9fe7308caa5ac3948c67c86ea7c41415a
kustomize build ./user-configuration/staging/e2e
```
