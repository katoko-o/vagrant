# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

#box名の設定
  config.vm.box = "bento/centos-7.3"

#プライベートipアドレスの設定
  config.vm.network "private_network", ip: "192.168.33.10", auto_config:false

#コネクションの設定
  config.vm.provider "virtualbox" do |vb|
     vb.customize ["modifyvm", :id, "--cableconnected1", "on"]  
  end
  
end
