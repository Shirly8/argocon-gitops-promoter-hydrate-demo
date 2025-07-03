# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 72d0ca4b93e022790b9d68f225ccebea633a59f9
kustomize build ./user-configuration/production/us-east-2
```
