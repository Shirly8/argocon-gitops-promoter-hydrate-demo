
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cba327aa7b7b1002fd222b274eaf39a5391017b6
kustomize build ./user-configuration/production/us-west-1
```