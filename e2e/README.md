
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3d05aaebd7ab34779df92ed7e52e4419de575ef7
kustomize build ./user-configuration/staging/e2e
```