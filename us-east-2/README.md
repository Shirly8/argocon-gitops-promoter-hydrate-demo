# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 585dc485c430e237a378b6335b3a899e5885fed9
kustomize build ./user-configuration/production/us-east-2
```
