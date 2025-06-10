
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout d295dca51b3220f6e80d401fc94b51c03afa0f73
kustomize build ./user-configuration/development
```