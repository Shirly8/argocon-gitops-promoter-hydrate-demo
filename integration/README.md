
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 15036ce7c1ee46e168d0a15d1d683cb001f1aa1b
kustomize build ./user-configuration/staging/integration
```