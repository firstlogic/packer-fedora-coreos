# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "fedora-coreos"
  config.vm.network "private_network", ip: "192.168.56.30"
  config.vm.synced_folder ".", "/vagrant", disabled: true
  config.ssh.username = "developer"
end
