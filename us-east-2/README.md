# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 179c101190939a15d291c151562477621f75c1db
kustomize build ./user-configuration/production/us-east-2
```
