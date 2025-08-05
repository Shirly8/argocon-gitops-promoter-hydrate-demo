# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5e324aaf7ab86faf3ac933a6558582d053edb595
kustomize build ./user-configuration/production/us-west-1
```
