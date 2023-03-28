# gatekeeper-playbooks

```
export BREW_USERNAME=<brew.registry.redhat.io user>
export BREW_PASSWORD=<brew.registry.redhat.io password>

ansible-playbook -e iib_number=<iib number> gatekeeper-brew.k8s.yml

ansible-playbook gatekeeper-config.k8s.yml

ansible-playbook gatekeeper-policies-namespace-label.k8s.yml

ansible-playbook -e '{"names": ["alpha", "beta"]}' httpd-deployment.k8s.yml
```