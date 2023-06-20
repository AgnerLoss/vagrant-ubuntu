Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |vb|
    vb.name = "ubuntu_20_04"
    vb.memory = 1024
    vb.cpus = 1
end
  config.vm.box = "bento/ubuntu-20.04"  
  config.vm.network "public_network", ip: "192.168.100.150", bridge: "eno1" 
  config.vm.synced_folder "site/", "/var/www/html/"  
end

