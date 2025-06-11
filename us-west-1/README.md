
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 804f2f35d699452442fe249920153146e4dfb74d
kustomize build ./user-configuration/production/us-west-1
```