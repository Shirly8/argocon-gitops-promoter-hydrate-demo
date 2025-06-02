
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 418f52bca86b97b59f583e783c507d582320fcba
kustomize build ./user-configuration/development
```