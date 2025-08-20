# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8ab185a4d5adb818f0bf28e059f479cb0db6bb37
kustomize build ./user-configuration/development
```
