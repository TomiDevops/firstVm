Vagrant.configure("2") do |config|
  config.hostmanager.enabled = true 
  config.hostmanager.manage_host = true
  # Every Vagrant development environment requires a box. You can search for
  config.vm.define "db02" do |db02|
  db02.vm.box = "eurolinux-vagrant/centos-stream-9"
  db02.vm.network "private_network", ip: "192.168.33.10"
  db02.vm.provider "virtualbox" do |vb|
  db02.vm.hostname = "db02"
  db02.vm.box_version = "9.0.43"
  #   # Customize the amount of memory on the VM:
   vb.memory = "600"
   end
end