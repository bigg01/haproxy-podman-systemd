# let podman do some haproxy



# init ansible
ansible-galaxy init --offline haproxy-podman

# install 
 ansible-playbook deploy.yaml --check
 ansible-playbook deploy.yaml 
