# Custom Ubuntu build using Ansible

The purpose of this project is to customize Ubuntu to contain the tools necesarry to play HackTheBox (HTB).

## Steps to install

1. Run an arbitrary sudo command to cache your sudo login
```
sudo whoami
```

2. Download roles from Ansible Galaxy
```
ansible-galaxy install -r requirements.yaml
```

3. Run the playbook
```
ansible-playbook main.yaml
```
