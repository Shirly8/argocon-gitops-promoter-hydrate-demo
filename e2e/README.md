# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e5d94f3ce6e2cfcd7dd28793705fa0d088616c02
kustomize build ./user-configuration/staging/e2e
```
