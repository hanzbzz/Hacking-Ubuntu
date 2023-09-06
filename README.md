# Custom Ubuntu build using Ansible

The purpose of this project is to customize Ubuntu to contain the tools necesarry to be usable to compete in CTF events.

## Steps to install

1. Run an arbitrary sudo command to cache your sudo login
```
sudo whoami
```

2. Download roles from Ansible Galaxy
```
ansible-galaxy install -r requirements.yml
```

3. Run the playbook
```
ansible-playbook main.yml
```

4. Once finished, restart the system
```
reboot
```

5. Enable the TopHat gnome extension
```
gnome-extensions enable tophat@fflewddur.github.io
```
