
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 34d36631f15bfb16218947e7ff0689f0844b947c
kustomize build ./user-configuration/staging/integration
```