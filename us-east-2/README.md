# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout aa5a2db28061d9d1ee53ef18526d768ae3f5e131
kustomize build ./user-configuration/production/us-east-2
```
