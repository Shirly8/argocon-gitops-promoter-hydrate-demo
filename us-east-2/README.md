
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 18027ee7971f6d759d739089acd0621615d15d45
kustomize build ./user-configuration/production/us-east-2
```