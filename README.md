# ansible-helm-diff

## How-To

### Clone the repository

```
git clone git@github.com:b44rawat/ansible-helm-diff.git
cd ansible-helm-diff
```

### Command to use

```
ansible-playbook -i inventory main.yaml --check --diff
```

## References

- https://docs.ansible.com/ansible/latest/collections/kubernetes/core/helm_module.html
- https://docs.ansible.com/ansible/latest/collections/kubernetes/core/helm_plugin_module.html
- https://docs.nginx.com/nginx-ingress-controller/installation/installation-with-helm/
- https://github.com/nginxinc/kubernetes-ingress/tree/v2.3.0
- https://artifacthub.io/packages/helm/nginx/nginx-ingress
