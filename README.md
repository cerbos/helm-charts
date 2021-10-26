Cerbos Helm Charts
==================

This repo hosts the [OCI registry](https://helm.sh/docs/topics/registries/) for Cerbos Helm charts. You need to use Helm 3.7 or above to access the charts hosted here.

```sh
export HELM_EXPERIMENTAL_OCI=1
helm install cerbos oci://ghcr.io/cerbos/helm-charts/cerbos --version=0.9.0
```

Cerbos helps you super-charge your authorization implementation by writing context-aware access control policies for your application resources. Find out more about Cerbos using the following resources:

* [Cerbos website](https://cerbos.dev)
* [Cerbos documentation](https://docs.cerbos.dev)
* [Cerbos GitHub repository](https://github.com/cerbos/cerbos)
* [Cerbos Slack community](http://go.cerbos.io/slack)
