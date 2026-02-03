# xibo-display

## Base System
- Ubuntu Server 24.04.3

```bash
sudo apt update
sudo apt install git ansible -y
```

## Configuration

Before running the playbooks, create your secrets file:

```bash
cp group_vars/all/secrets.yml.example group_vars/all/secrets.yml
```
