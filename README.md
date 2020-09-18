# MongoDB Community Kubernetes Operator Chart

This is a [Helm Chart](https://helm.sh/) that enables deployment of the
[MongoDB Community Kubernetes Operator](https://github.com/mongodb/mongodb-kubernetes-operator)
using Helm.

# Install

This chart has only been tested with Helm 3.0+. You can install this chart
directly from this repository using the [helm-git](https://github.com/aslafy-z/helm-git)
plugin:

    $ helm plugin install https://github.com/aslafy-z/helm-git --version 0.8.1

Then, add the repository:

    $ helm repo add mongodb-kubernetes-operator-chart git+https://github.com/glints-dev/mongodb-kubernetes-operator-chart

Finally, install the chart:

    $ helm install mongodb-kubernetes-operator-chart/mongodb-kubernetes-operator --namespace=<namespace>

# License

Please see the [LICENSE](LICENSE) file.

