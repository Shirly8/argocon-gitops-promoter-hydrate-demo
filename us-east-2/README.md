# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6be550bbca1d152821d93d31cb6ba3b16c967170
kustomize build ./user-configuration/production/us-east-2
```
