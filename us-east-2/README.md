# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3c7cdfa04451feba2e22a4a37639d28b5df8e55e
kustomize build ./user-configuration/production/us-east-2
```
