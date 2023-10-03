# GitOps Instances

## Cluster: openshift-gitops namespace instance

To manage config of the core instance of OpenShift GitOps with OpenShift GitOps :)

```
oc apply -k https://github.com/pittar-demos/demo-catalog/openshift-gitops-instances/argocd/openshift-gitops
```

Once Argo CD is up and running in the `openshift-gitops` namespace, you're ready to setup your demos!

## Developer: gitops namespace instance

```
oc apply -k https://github.com/pittar-demos/demo-catalog/openshift-gitops-instances/argocd/gitops
```