# ansible_smartcs
Zero Touch Provisioning for Ansible + SmartCS + Cisco Catalyst 2960

Presentation + Demo: TBD

## Demo 1: Change hostname for factory-default Catalyst 2960
```
ansible-playbook playbook_change_hostname.yml -i inventory
```

## Demo 2: Set standard configuration for factory-default Catalyst 2960

```
ansible-playbook playbook_ztp.yml -i inventory
```

## SmartCS config for ansible + smartcs demo
see [this config](./smartcs_config.txt)