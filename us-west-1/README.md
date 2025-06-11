
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aeb488aa0baf3b75dc13db13ec3d21504523fd38
kustomize build ./user-configuration/production/us-west-1
```