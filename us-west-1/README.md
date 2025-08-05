# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f2fa606b4928104a8bfe7ad46e61abff7d9ebf9d
kustomize build ./user-configuration/production/us-west-1
```
