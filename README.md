
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f70eaec926fe18f221fb18f85707ce528dd28820
kustomize build ./user-configuration/development
```