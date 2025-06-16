# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7a549d97988b1011aa90ff948515ecddcbe56bea
kustomize build ./user-configuration/production/us-west-1
```
