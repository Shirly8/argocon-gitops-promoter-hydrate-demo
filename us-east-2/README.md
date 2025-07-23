# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a5c582dc62f20c842bf14b3d4086d9d67d215e42
kustomize build ./user-configuration/production/us-east-2
```
