
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 4a541cfcfbf90405383c36c1a4ae42271ab666f9
kustomize build ./user-configuration/production/us-east-2
```