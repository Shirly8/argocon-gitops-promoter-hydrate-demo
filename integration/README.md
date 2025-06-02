
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ba0d401869651a49bba325e9d009687b971658b1
kustomize build ./user-configuration/staging/integration
```