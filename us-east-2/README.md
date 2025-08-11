# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bf86c79dd305b85fac0264d5807e9123a816858d
kustomize build ./user-configuration/production/us-east-2
```
