
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7497f19e476675a3f538277056b2224c642d2ee9
kustomize build ./user-configuration/production/us-east-2
```