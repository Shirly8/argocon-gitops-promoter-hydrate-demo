
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c1bdf5dae5787f8f31db3fc2a682f7f3c2d951d8
kustomize build ./user-configuration/production/us-west-1
```