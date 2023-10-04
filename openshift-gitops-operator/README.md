# OpenShift GitOps Operator

Installs the OpenShift GitOps (Argo CD) operator.

Do not use the `base` directory directly, as you will need to patch the `channel` based on the version of OpenShift you are using, or the version of the operator you want to use.

The current *overlays* available are for the following channels:
* [latest](overlays/latest)
* [gitops-1.8](overlays/gitops-1.8)
* [gitops-1.9](overlays/gitops-1.9)
* [gitops-1.10](overlays/gitops-1.10)
