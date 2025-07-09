# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fa1f80a10686ba48bc2b348e8c3ed4a9c1b6ad7c
kustomize build ./user-configuration/production/us-east-2
```
