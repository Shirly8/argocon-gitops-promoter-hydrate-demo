# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 55a01e41cd7731aee81e1b9bcf9ea2d02bd8fc00
kustomize build ./user-configuration/production/us-west-1
```
