
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2e6fd36ad5e8344d5301ffa16bfc71b4fb9c4bc4
kustomize build ./user-configuration/production/us-west-1
```