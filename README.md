# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 479bd5065185379089ab4ed7bc7ec05f09d92b2b
kustomize build ./user-configuration/development
```
