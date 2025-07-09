# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c6ff1504ea9f2a7d45b01834ef88c62fdaed5488
kustomize build ./user-configuration/development
```
