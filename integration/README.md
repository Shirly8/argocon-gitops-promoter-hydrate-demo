# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3ef1ce6a5cee7bac4e94bbfa576c879c47b371d6
kustomize build ./user-configuration/staging/integration
```
