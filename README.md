# kubeztl

Trying to simplify th eintegration of the ziti wrapper around the kubectl source code created under the openziti kitchen located 
in [this repo](https://github.com/openziti-test-kitchen/kubectl). The idea is to have a go kubeztl wrapper that links to 
[the latest kubectl cmd package](https://pkg.go.dev/k8s.io/kubectl/pkg/cmd) not being compiled at a certain point of time. 
