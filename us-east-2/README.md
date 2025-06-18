# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8b0359e048cba24b653c60b8a729944506914149
kustomize build ./user-configuration/production/us-east-2
```
