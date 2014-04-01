VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "vm1" do |web|
    web.vm.box = "jubianchi/php-55"
    config.vm.network :private_network, ip: "192.168.50.10"
    config.vm.provision "shell", path: "provision.sh" 
  end

  config.vm.define "vm2" do |db|
    db.vm.box = "jubianchi/php-55"
    config.vm.network :private_network, ip: "192.168.50.11"
    config.vm.provision "shell", path: "provision.sh" 
  end
end

