
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8597ab136b8fc7ef328d90b5776dd06397b26dee
kustomize build ./user-configuration/staging/integration
```