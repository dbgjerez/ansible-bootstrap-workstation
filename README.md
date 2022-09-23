# Installation
## Fedora

```bash
sudo dnf install ansible
```

## Ubuntu
```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

# Run

```
ansible-playbook -i localhost playbook.yaml -K
```

> Note: -K option ask for the root user password
