Role Name
=========

Deploy the latest `Debian 10` VM on Proxmox VE host.

How to
------
```bash
ansible-playbook ./deploy_debian10_on_proxmox.yml \
-e working_host=proxmox.example.com \
-e ansible_ssh_port=22 \
-e storage=local-zfs \
-e VM_ID=1111 \
-e network_bridge-vmbr0
```

- `ansible_ssh_port`, `storage` and `network_bridge` is set by default.