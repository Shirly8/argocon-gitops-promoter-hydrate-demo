# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 77877ebfaffb326378b78ba7bb46fb8a1031f55f
kustomize build ./user-configuration/development
```
