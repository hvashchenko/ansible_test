Libvirt VM
================
This role configures and creates (or destroys) VMs on a KVM hypervisor.

Requirements
================
The host should have Virtualization Technology (VT) enabled and should be preconfigured with libvirt/KVM.

Running Playbook
================
```
ansible-playbook -c paramiko bootstrap.yml --vault-password-file=password_file

```
Destroy VmsPlaybook
================
``````
ansible-playbook -c paramiko destroy.yml

```
