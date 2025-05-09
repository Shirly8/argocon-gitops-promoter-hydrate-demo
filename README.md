
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 131d15c3148cbfbff54453a31b65e2a98614d625
kustomize build ./user-configuration/development
```