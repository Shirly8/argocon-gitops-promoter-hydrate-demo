
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 476a50c47d889cf3011a2120391d8ef096f2efe5
kustomize build ./user-configuration/development
```