
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 17877b7c737827a267542b72ae41a11287b51ba0
kustomize build ./user-configuration/production/us-west-1
```