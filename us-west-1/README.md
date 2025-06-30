# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 83acd2e40b74fc6df9b43725afd613d164c4e28b
kustomize build ./user-configuration/production/us-west-1
```
