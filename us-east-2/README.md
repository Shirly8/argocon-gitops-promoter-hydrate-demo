
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63e28969dbcfceb4615b2b922e2c649748324578
kustomize build ./user-configuration/production/us-east-2
```