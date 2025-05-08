
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e1fc81b6813424846b208c5e5827762c99e1a5de
kustomize build ./user-configuration/development
```