# let podman do some haproxy



# init ansible
ansible-galaxy init --offline haproxy-podman

# install 
ansible-playbook   tasks/deploy.yaml --check