
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7eb0d20aca6c8c5c910acd6fe738d8f6114293ed
kustomize build ./user-configuration/development
```