Vagrant.configure("2") do |config|
  config.vm.define "cdevops" do |devbox|
    devbox.vm.box = "mialeevs/centos8"
    devbox.vm.box_version = "1.0.0"
    devbox.vm.hostname = "csrvp"
    devbox.vm.provider "virtualbox" do |vb|
      vb.memory = 4096
      vb.cpus = 2
    end
  end
end
