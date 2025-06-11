
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 0874f778823c50b04c4c46e15b2a6ec8bd8544d5
kustomize build ./user-configuration/staging/integration
```