
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 62bb8da9d7ad7273ff3a71ba815aa1b6811319b9
kustomize build ./user-configuration/production/us-west-1
```