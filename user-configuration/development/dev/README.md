# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7ba35a9d010cac8951a018041f721f3b3888ca3a
kustomize build ./user-configuration/development
```
