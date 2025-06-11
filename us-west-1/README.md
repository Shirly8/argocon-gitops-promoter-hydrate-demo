
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0a6be8b1d46bc8ec8561f5d57cc1419af4b8c06c
kustomize build ./user-configuration/production/us-west-1
```