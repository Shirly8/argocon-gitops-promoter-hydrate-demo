
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0ef7fc89558eac3b7cb2085c462288c92e022245
kustomize build ./user-configuration/production/us-west-1
```