# OpenShift Pipelines Operator

Installs the OpenShift Pipelines (Tekton) operator.

Do not use the `base` directory directly, as you will need to patch the `channel` based on the version of OpenShift you are using, or the version of the operator you want to use.

The current *overlays* available are for the following channels:
* [latest](overlays/latest)
* [pipelines-1.11](overlays/pipelines-1.11)
* [pipelines-1.11](overlays/pipelines-1.12)

## Cluster: openshift-gitops namespace instance

To manage config of the core instance of OpenShift GitOps with OpenShift GitOps :)

```
oc apply -k https://github.com/pittar-demos/demo-catalog/openshift-pipelines-operator/argocd
```
