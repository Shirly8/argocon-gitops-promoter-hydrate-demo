
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b958725508791a96e3719481f80b329ebf98715b
kustomize build ./user-configuration/development
```