
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1d570fe376505eca059460095165041839d2ee0e
kustomize build ./user-configuration/staging/e2e
```