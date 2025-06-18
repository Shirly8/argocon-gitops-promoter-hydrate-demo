# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 29ad1d8e0abfb3a6b29339ba0d9314c5959223ed
kustomize build ./user-configuration/production/us-east-2
```
