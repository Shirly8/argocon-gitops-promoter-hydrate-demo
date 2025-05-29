
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 75df432fc426eada5f3dca289ea9aa3cae3c4b17
kustomize build ./user-configuration/development
```