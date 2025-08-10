# Xray

## Install ansible
apt install ansible

## Install Xray 
ansible-playbook -i 127.0.0.1 xray_install.yml

## Add new client (qr + text key)
ansible-playbook -i 127.0.0.1 add_client.yml
