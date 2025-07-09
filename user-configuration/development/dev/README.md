# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 62c94fb372adcddcab9e345e79664c1c4874b0b0
kustomize build ./user-configuration/development
```
