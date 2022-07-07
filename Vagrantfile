Vagrant.configure(2) do |config|
  config.vm.define "centosvm" do |centosvm|
    centosvm.vm.box = "centos/7"
    centosvm.vm.hostname = "centosvm"
    centosvm.vm.network "private_network", ip: "192.168.70.2"
    centosvm.vm.network "public_network",
      use_dhcp_assigned_default_route: true
    centosvm.vm.provider "virtualbox" do |v|
      v.name = "centosvm"
      v.memory = 16200
      v.cpus = 6
    end
  end
end


