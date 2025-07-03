# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 59f2ac5b55a87998a5680d613a66752cc8a9a416
kustomize build ./user-configuration/production/us-west-1
```
