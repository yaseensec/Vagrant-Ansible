This repo contains Ansible Playbooks,which uses Vagrant,Libvirt and Ansible to boot and configure VM's on Local Workstation


### 1 - Install dependencies (KVM-QEMU-Libvirt, Vagrant, Ansible)

  1. Setup KVM,QEMU,Libvirt in your Distro (Arch Linux Setup link) [KVM-QEMU-Libvirt](https://www.howtoforge.com/how-to-install-kvm-qemu-on-manjaro-archlinux/).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. Setup Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### 2 - Build the Virtual Machine

  1. Download this repo
  2. Open Terminal, cd one of the subdirs (containing the `Vagrantfile` and this README file).
  3. Type in `vagrant up`, to spin up VM,but make sure to change the config as per requirements.
  4. cd into provisioning dir and run ansible-playbook command along with playbook


