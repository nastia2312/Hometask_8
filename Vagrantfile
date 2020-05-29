Vagrant.configure("2") do |config|
 config.vm.define "host_1" do |host_1|
  host_1.vm.box = "ubuntu/bionic64"
  host_1.vm.network "private_network", ip: "192.168.3.2"
 end
 config.vm.define "host_2" do |host_2|
  host_2.vm.box = "ubuntu/bionic64"
  host_2.vm.network "private_network", ip: "192.168.3.3"
 end
end
