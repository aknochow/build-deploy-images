# build-deploy-images
Build Images from Github Source and Deploy to a Kubernetes cluster

Currently builds:
- awx
- awx-operator
- pulp-operator

Run playbook with a vars file for an image:

_build an operator:_

`ansible-playbook build-deploy-operator.yaml -e "@vars_awx-operator.yaml"`

_build awx:_

`ansible-playbook build-deploy-awx.yaml`
