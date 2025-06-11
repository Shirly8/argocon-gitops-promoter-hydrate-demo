
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ff17d12e58c5f83f555e2aba7b36f876544e7fdc
kustomize build ./user-configuration/production/us-east-2
```