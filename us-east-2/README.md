# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 6ba87e18c96c245b920d6e8bddf914ede78bf06f
kustomize build ./user-configuration/production/us-east-2
```
