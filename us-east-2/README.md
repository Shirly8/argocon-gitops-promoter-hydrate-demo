
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e07f478ef08ab404bc1be96ba4b7f2fbec75dd36
kustomize build ./user-configuration/production/us-east-2
```