
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e0357ec66c1367cbe1dbd8771c4da88d91812f63
kustomize build ./user-configuration/development
```