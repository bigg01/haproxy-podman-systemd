# let podman do some haproxy



# init ansible
```sh
ansible-galaxy init --offline haproxy-podman
```
# install 
```sh
 ansible-playbook deploy.yaml --check
 ansible-playbook deploy.yaml 
```
