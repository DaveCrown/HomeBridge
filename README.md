# Home Bridge Ansible plays
## Introduction
The purpose of this repo is to store my configuration management for use with Homebridge , Ansible, and Tower.

## Usage
```ansible-playbook install_homebridge.yml -e " extra_vars "```
### Vars
Name | Value | Purpose 
--- | --- | ---
homebridge_name | simple string | sets display name
config_repo | git url | Triggers loading device types
homebridge_pin | default 031-45-154 | Sets the device enrollment pin

## Legal Stuff
This is no way affiliated with the HomeBridge project