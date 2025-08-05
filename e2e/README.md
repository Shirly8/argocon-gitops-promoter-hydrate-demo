# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 5262c1b5fb84f65665417824e54232fb6ed5e6de
kustomize build ./user-configuration/staging/e2e
```
