# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c84e868ceb20358d28815333c8847ad1e90c6eec
kustomize build ./user-configuration/staging/e2e
```
