# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cac580ea6dcb8642c997b98279c29b59f9bdebe0
kustomize build ./user-configuration/production/us-east-2
```
