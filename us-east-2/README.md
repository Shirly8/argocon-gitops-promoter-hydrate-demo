# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4f904f5e834ec10396c19c1555c27bc5f17ef2a6
kustomize build ./user-configuration/production/us-east-2
```
