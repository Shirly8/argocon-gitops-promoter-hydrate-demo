# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6242d14f63f6e6ad38e33e2f599fffa801623839
kustomize build ./user-configuration/development
```
