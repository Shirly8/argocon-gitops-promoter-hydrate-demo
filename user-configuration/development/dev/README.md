# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ab8888d81739373ae239016500d9571c1f56bc3f
kustomize build ./user-configuration/development
```
