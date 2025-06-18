
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b3ca6088b1335123bdd016d6e26955587fc23a68
kustomize build ./user-configuration/production/us-east-2
```