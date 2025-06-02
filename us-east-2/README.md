
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 98d3cdc74887f880d3ba58d25fcc0b8699ad2eb5
kustomize build ./user-configuration/production/us-east-2
```