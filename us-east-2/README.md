# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3b64b47024dcf729c3fdeb9e6599140d56489906
kustomize build ./user-configuration/production/us-east-2
```
