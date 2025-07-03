# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 505e40a88d53e6ba5d0048dbab7546da2093b076
kustomize build ./user-configuration/development
```
