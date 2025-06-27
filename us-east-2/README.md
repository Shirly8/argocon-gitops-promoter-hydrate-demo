# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cc0f83584b150dfd613465c18bc7df86bd6080c5
kustomize build ./user-configuration/production/us-east-2
```
