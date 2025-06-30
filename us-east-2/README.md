# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e2b5f42914ef6a0eba9100a58246c1605dcbd634
kustomize build ./user-configuration/production/us-east-2
```
