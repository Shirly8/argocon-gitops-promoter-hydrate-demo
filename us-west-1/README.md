# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout c7c4906ca7cd2e83cdfe476d945991b305bf96d8
kustomize build ./user-configuration/production/us-west-1
```
