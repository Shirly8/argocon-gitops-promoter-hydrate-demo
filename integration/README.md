# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cc7c70abb652b26aabc6e265b7b8107e6f6219bd
kustomize build ./user-configuration/staging/integration
```
