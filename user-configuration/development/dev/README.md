# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout cb408829768fdbd404cdad705167e4492a57632f
kustomize build ./user-configuration/development
```
