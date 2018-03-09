Vagrant.configure("2") do |config|
config.vm.define "node2" do |node2|
node2.vm.box = "bento/centos-6.7"
node2.vm.network :private_network, ip: "192.168.56.2"
#node2.vm.hostname = "node2.mylab.local"
#cd cdconfig.vm.boot.timeout = "1500"
end
config.vm.define "node3" do |node3|
node3.vm.box = "ubuntu/trusty64"
node3.vm.network :private_network, ip: "192.168.56.3"
#node3.vm.hostname = "node3.mylab.local"
end
end