# build-deploy-images
Build Images from Github Source and Deploy to a Kubernetes cluster

Currently builds:
- awx
- awx-operator
- pulp-operator

#### Build

_operator:_

`ansible-playbook build-deploy-operator.yaml -e "@vars_awx-operator.yaml"`

_awx:_

`ansible-playbook build-deploy-awx.yaml`
