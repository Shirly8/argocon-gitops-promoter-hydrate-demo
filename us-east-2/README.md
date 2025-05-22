
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 1423185b641d843b8627a3adc793701097c03ec4
kustomize build ./user-configuration/production/us-east-2
```