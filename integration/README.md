# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout de719db18b2f7b6d81db4e312ec37708bf569dd8
kustomize build ./user-configuration/staging/integration
```
