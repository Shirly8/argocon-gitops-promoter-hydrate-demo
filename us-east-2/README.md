# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 022c712856e55c4247bfe0c0738b740d4b16df2b
kustomize build ./user-configuration/production/us-east-2
```
