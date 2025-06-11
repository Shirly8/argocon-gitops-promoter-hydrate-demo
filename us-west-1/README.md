
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a34276d3a65e68403e6e8d078e4880983852f7c2
kustomize build ./user-configuration/production/us-west-1
```