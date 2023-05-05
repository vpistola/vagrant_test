# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "master" do |node|
    node.vm.hostname = "master"
    node.vm.box = "hashicorp/bionic64"
    node.vm.network "private_network", ip: "192.168.33.10"
    node.vm.provider "virtualbox" do |vb|
      vb.cpus = 2
      vb.memory = "1024"
    end
  end

  config.vm.define "node1" do |node|
    node.vm.hostname = "slave-s1"
    node.vm.box = "hashicorp/bionic64"
    node.vm.network "private_network", ip: "192.168.33.11"
    node.vm.provider "virtualbox" do |vb|
      vb.cpus = 2
      vb.memory = "1024"
    end
  end

  config.vm.define "node2" do |node|
    node.vm.hostname = "slave-s2"
    node.vm.box = "hashicorp/bionic64"
    node.vm.network "private_network", ip: "192.168.33.12"
    node.vm.provider "virtualbox" do |vb|
      vb.cpus = 2
      vb.memory = "1024"
    end
  end
end