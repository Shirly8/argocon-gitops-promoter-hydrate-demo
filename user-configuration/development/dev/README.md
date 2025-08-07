# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f0cdb61a140a3b88d60cbeb2bbb320d7ba0ba9cb
kustomize build ./user-configuration/development
```
