# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f2518a6e7f0038160c60c8246aaf20f8d6868d2c
kustomize build ./user-configuration/production/us-west-1
```
