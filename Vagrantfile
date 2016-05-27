# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  # Refs http://www.vagrantbox.es/
  config.vm.box = "https://f0fff3908f081cb6461b407be80daf97f07ac418.googledrive.com/host/0BwtuV7VyVTSkUG1PM3pCeDJ4dVE/centos7.box"

  config.vm.define :hoge do |v|
    v.vm.network :private_network, ip: "192.168.33.10"
    v.vm.hostname = "sandbox01"

    v.vm.provider "virtualbox" do |vb|
      vb.name = "sandbox01"
      vb.memory = 512
    end
  end
end
