# make-image-ubuntu

This Ansible playbook configures an Ubuntu server to be used as a Proxmox VE image. To use, start by installing Ansible:

```
$ sudo apt install ansible
```

Then run `ansible-pull` like so:

```
$ ansible-pull -K -U https://github.com/charlieuniformtango/make-image-ubuntu.git
```
