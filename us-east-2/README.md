
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout bdc3379ede2a0d5d5718db6f52e1c617c9a10317
kustomize build ./user-configuration/production/us-east-2
```