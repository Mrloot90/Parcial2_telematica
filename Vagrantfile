Vagrant.configure("2") do |config|
  config.vm.define :clienteFw do |clienteFw|
  clienteFw.vm.box = "bento/centos-7.9"
  clienteFw.vm.network :private_network, ip: "209.191.100.2"
  clienteFw.vm.hostname = "clienteFw"
  end
  config.vm.define :firewall do |firewall|
  firewall.vm.box = "bento/centos-7.9"
  firewall.vm.network :private_network, ip: "209.191.100.3"
  firewall.vm.network :private_network, ip: "192.168.100.3"
  firewall.vm.hostname = "firewall"
  end
  config.vm.define :servidor2 do |servidor2|
  servidor2.vm.box = "bento/centos-7.9"
  servidor2.vm.network :private_network, ip: "192.168.100.4"
  servidor2.vm.hostname = "servidor2"
  end
  end