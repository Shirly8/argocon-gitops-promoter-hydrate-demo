# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b585b86de054a1056e0959961376d144db6c2629
kustomize build ./user-configuration/staging/integration
```
