# xibo-display

## Base System
Ubuntu Server 24.04.3

```bash
sudo apt update && sudo apt install git ansible -y
```

## Clone This Repository
```bash
git clone https://github.com/swasilan/xibo-display.git
```

## Configuration

Before running the playbooks, create your secrets file:

```bash
cp group_vars/all/secrets.yml.example group_vars/all/secrets.yml
```
