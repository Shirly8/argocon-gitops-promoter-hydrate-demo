
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 268d8c522000e3ccde5fb9a328e73d82e829d87e
kustomize build ./user-configuration/staging/integration
```