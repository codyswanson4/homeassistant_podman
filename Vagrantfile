Vagrant.configure("2") do |config|
  config.vm.box = "generic/fedora37"
  config.vm.network "forwarded_port", guest: 8123, host: 8123, host_ip: '127.0.0.1'
  # Enable provisioning with a shell script. Additional provisioners such as
  # Ansible, Chef, Docker, Puppet and Salt are also available. Please see the
  # documentation for more information about their specific syntax and use.
  # config.vm.provision "shell", inline: <<-SHELL
  #   apt-get update
  #   apt-get install -y apache2
  # SHELL
end
