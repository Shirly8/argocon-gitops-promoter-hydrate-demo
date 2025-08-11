# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3bac0d0fd587a74dfd1773147067f0fff3584ac5
kustomize build ./user-configuration/development
```
