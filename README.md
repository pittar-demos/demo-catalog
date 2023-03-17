# GitOps Demo Catalog

Inspired by the [Red Hat CoP GitOps Catalog](), but a smaller version that is specific to my own demos.

## Getting Started

If you're starting with OpenShift GitOps, then run the following command to deploy Argo CD:

```
oc apply -k https://github.com/pittar-demos/demo-catalog/openshift-gitops-operator/overlays/<channel>
```

Once Argo CD is up and running in the `openshift-gitops` namespace, you can proceed.