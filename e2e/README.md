# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 66f7d572fb9e8fd9e0bbc0b73b781ffdccbe97ec
kustomize build ./user-configuration/staging/e2e
```
