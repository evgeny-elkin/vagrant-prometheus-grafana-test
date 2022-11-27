# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrant config for test case: Install and run Prometheus and Grafana in docker containers on Ubuntu 20.04

Vagrant.configure("2") do |config|

# Right vagrant box
  config.vm.box = "generic/ubuntu2004"

# Port 3000 forwarding for Grafana
  config.vm.network "forwarded_port", guest: 3000, host: 3000, host_ip: "127.0.0.1"
  
# Ansible provisioning via playbook file 
  config.vm.provision "ansible", run: "always" do |ansible|
    ansible.playbook="playbook.yaml"
  end

end
