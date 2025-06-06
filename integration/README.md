
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 552cad7e2c36609e0b74bd86b869e58634c8b922
kustomize build ./user-configuration/staging/integration
```