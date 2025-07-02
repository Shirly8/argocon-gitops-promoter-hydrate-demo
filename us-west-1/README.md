# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 84f6b398eb27070c136075c28b460a1c26c19bb3
kustomize build ./user-configuration/production/us-west-1
```
