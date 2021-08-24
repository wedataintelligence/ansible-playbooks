Role Name
=========

A brief description of the role goes here.

How to
------
```bash
ansible-playbook ./deploy_kali_on_proxmox.yml -e working_host=proxmox.example.com -e ansible_ssh_port=22 -e storage=local-zfs -e VM_ID=1111 -e network_bridge-vmbr0 -e image_version=2021.2
```

- `ansible_ssh_port`, `storage`, `network_bridge` and `image_version` is set by default.