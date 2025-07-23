# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 977246f4a602d81976c155170c34616d574df640
kustomize build ./user-configuration/production/us-east-2
```
