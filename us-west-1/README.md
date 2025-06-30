
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8f1d5fab4fac075e747d3d98e00a42e04efbc8cf
kustomize build ./user-configuration/production/us-west-1
```