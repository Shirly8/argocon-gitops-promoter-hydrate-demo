# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bc2fe63f02cb75d8e7b6bff6e7980189aa3258d3
kustomize build ./user-configuration/development
```
