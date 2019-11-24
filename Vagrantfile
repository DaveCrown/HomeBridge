Vagrant.configure("2") do |config|
  config.vm.box = "debian/buster64"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "install_homebridge.yml"
    ansible.extra_vars = {
      homebridge_name: "CrownHaus",
    }

  end
  config.vm.network "forwarded_port", guest: 8080, host: 8080
end