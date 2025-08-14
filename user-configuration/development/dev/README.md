# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b723896a8073fef05c4da709284be3d55746d4b6
kustomize build ./user-configuration/development
```
