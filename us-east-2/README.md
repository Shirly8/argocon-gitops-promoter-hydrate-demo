# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2e133428328b64e750f840296ab2e05ea6c9c110
kustomize build ./user-configuration/production/us-east-2
```
