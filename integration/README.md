
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b6e62d252df3c63c35a42446aeb5938ab4183192
kustomize build ./user-configuration/staging/integration
```