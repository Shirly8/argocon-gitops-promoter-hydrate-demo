# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 09ad1a4bdb3e7614ea8b2505d036b614d51395a6
kustomize build ./user-configuration/development
```
