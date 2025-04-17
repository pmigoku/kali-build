# Kali Setup Ansible Playbook
Ansible playbooks to setup kali for OSCP and other pentesting labs. This is configured to run locally on the the kali box.

Tested on Kali 2025.1

# Instructions

update and install ansible
```bash
sudo apt update && sudo apt install ansible -y
```

clone git repo
```bash
git clone https://github.com/ch3go/kali-build.git
```

run playbook 
```bash
ansible-playbook kali_setup.yml -K
```


