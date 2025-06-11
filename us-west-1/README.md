
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 384368c18aeb6d3fbdbc37e680d905d800256bab
kustomize build ./user-configuration/production/us-west-1
```