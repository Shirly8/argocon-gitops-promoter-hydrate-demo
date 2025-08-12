# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ed8e4381cb3cce407b3a90308819cd18fb91b595
kustomize build ./user-configuration/development
```
