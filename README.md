# xibo-display

## Base System

Install following Linux Distro:
- Ubuntu Server 24.04.3

Before beginning, run following commands:

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

## Installation

Make install.sh executable

```bash
cd xibo-display
chmod +x install.sh
```

Execute install.sh

```bash
./install.sh
```
