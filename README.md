Launch playbook with tag:
- first_server_node : init first server node
- server_node : init other server node
- worker_node : init k3s worker node

Launch playbook with tag and extra vars (api_endpoint and api_port is mandatory):
```
ansible-playbook site.yml -t TAG --extra-vars "api_endpoint=https://enpoint.com" "api_port=6443"
```