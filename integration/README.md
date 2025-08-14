# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2e1dbd6b1765309da4705f3bc6d03d03c2315b1c
kustomize build ./user-configuration/staging/integration
```
