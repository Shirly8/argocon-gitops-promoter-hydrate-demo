
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 84829b2994650b8318721b7a85330dd260a8c22e
kustomize build ./user-configuration/staging/e2e
```