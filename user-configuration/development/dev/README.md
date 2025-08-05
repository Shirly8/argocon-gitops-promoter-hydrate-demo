# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 44d2090ad83586d93a3ce3f8b7dc6f6c1432543f
kustomize build ./user-configuration/development
```
