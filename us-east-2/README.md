
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9d868ae33998803722bd63f58666d0416d13b72d
kustomize build ./user-configuration/production/us-east-2
```