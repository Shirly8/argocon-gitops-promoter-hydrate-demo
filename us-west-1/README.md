# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7e6d1a8f8fac86a1684aea6c5a2d825f8ecce5f9
kustomize build ./user-configuration/production/us-west-1
```
