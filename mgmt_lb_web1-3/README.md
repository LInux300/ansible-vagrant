# Ansible Vagrant


## VagrantCloud
## Provider: libvirt
https://app.vagrantup.com/boxes/search?provider=libvirt
https://app.vagrantup.com/ceph/boxes/ubuntu-xenial

# Initial Vagrant
sudo systemctl restart nfs-server.service
vagrant up


#to overcome the authentication of host
ssh-keyscan lb web1 web2 web3 >> .ssh/known_hosts_


## VM Webs 
- install 4 virtual machines
-- install Ansible on mgmt node
-- second one is load balancer
-- last two are web servers
-- examples contains Code Snippets
-- bootstrap-mgmt.sh - Install/Config Ansible & Deploy Code Snippets

