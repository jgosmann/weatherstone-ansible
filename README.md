# Weatherstone Ansbile configuration

Ansible playbook to configure my "weatherstone" Raspberry Pi with environmental
sensors (BME-680 for temperature, humidity, pressure, VOC; MH-Z19C for CO2).

## Setup

```bash
ansible-galaxy install -r requirements.yml
```

## Usage

```bash
ansible-playbook -i hosts setup.yml
```