# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fe7f852933bba4c67000c6f18006365c35025ca0
kustomize build ./user-configuration/production/us-east-2
```
