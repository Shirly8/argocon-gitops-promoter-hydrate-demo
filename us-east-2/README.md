# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 63722ab4bf659dd99763cc7c560f148f683798f0
kustomize build ./user-configuration/production/us-east-2
```
