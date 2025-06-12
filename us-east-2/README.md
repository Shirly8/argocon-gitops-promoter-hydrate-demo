
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a78a2798328471efaa95fb5d86059a35f798545e
kustomize build ./user-configuration/production/us-east-2
```