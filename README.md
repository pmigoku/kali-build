# Kali Setup Ansible Playbook
Ansible playbooks to setup kali for OSCP and other pentesting labs. This is configured to run locally on the the kali box.

# Instructions
```bash
# update and install ansible
sudo apt update && sudo apt install ansible -y

# clone git repo
git clone https://github.com/ch3go/kali-build.git

# run playbook locally
ansible-playbook kali_setup.yml -K

```
