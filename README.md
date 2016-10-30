vagrant-centos-docker
==================================

Vagrantfile for CentOS docker host

Usage
----------------------------------
```
vagrant up
vagrant ssh
sudo docker run --rm hello-world
```

Troubleshoot
----------------------------------

- Ensure Vagrant is the latest version.

- Ensure VirtualBox is the latest version supported by Vagrant.

- Execute commands following:

  ```
  vagrant box update
  vagrant vbguest --do install
  vagrant reload --provision
  ```
