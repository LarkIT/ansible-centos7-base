# Lark IT Ansible Linux Base Role

Default configuration for all Linux machines administered by Lark IT

## Operating Systems
This role is known to work on the following operating systems:
- CentOS 7

## Dependencies
None

## Variables
| Variable | Required? | Default Value | Type | Description |
|----------|--------|-------|------|--------|
| hostname | Required | - | String | The machine's hostname will be set to this value |
| vmware | Optional | False | Boolean | Whether or not to install VMware tools, enable when virtualized on top of VMware |
