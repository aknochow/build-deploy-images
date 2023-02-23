# build-deploy-images
Build Images from Github Source and Deploy to a Kubernetes cluster

Examples:
- awx-operator
- pulp-operator

Run playbook with a vars file for an image:

_example:_

`ansible-playbook build-deploy.yaml -e "@vars_awx-operator.yaml"`
