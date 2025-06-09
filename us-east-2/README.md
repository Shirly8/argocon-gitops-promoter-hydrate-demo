
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout fb2eadc24212bdf54f3f9cf71f047dbbb0bea6a0
kustomize build ./user-configuration/production/us-east-2
```