# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63e93478bf9bd55c498dd19cd785728f67d6e2ac
kustomize build ./user-configuration/staging/integration
```
