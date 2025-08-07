# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2555d020fae7e1f19516181dbaf445e6012f4e43
kustomize build ./user-configuration/production/us-west-1
```
