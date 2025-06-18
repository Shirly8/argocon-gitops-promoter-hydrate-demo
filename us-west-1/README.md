
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 8c29c6af8bcdf6435355fa7ef7e94e18da929a27
kustomize build ./user-configuration/production/us-west-1
```