
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 10d71ea4506123447a36b96fd47d58550f478791
kustomize build ./user-configuration/production/us-east-2
```