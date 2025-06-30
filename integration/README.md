# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 37780a00d55bdae05cad70f05509a96214e1f067
kustomize build ./user-configuration/staging/integration
```
