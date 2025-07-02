# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e24d9ae9f7c45276bd8c527e6b2b0d0d7c55a8ae
kustomize build ./user-configuration/production/us-east-2
```
