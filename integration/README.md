
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6b86fbf14612683a9c957b347b695e1e6f0f2bab
kustomize build ./user-configuration/staging/integration
```