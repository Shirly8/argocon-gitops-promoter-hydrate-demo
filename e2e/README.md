# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e21a61a12ae50197f43bfb3295066d1b4f7b03eb
kustomize build ./user-configuration/staging/e2e
```
