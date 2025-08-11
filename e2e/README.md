# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 068679e7572b0c42aa5b0c3c23bccbebfd7b7f42
kustomize build ./user-configuration/staging/e2e
```
