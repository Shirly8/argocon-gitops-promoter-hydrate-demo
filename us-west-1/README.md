
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/Shirly8/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout dda69304b2db8ca213e7a869395d6aab231f54ed
kustomize build ./user-configuration/production/us-west-1
```