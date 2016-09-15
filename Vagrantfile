Vagrant.configure(2) do |config|
  config.vm.box = "bento/centos-7.2"

  config.vm.provision "shell", inline: <<-SHELL
    sudo yum update -y
  SHELL

  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "install-docker.yml"
    ansible.inventory_path = "inventory"
    ansible.limit = "all"
  end

end
