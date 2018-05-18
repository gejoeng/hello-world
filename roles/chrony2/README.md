# Ansible Role: chrony

Manages the chrony services. Chrony is a service for keeping the time of your systems in sync.

## Variables

- chrony_ntp_servers: list of ntp servers

## Example 

    - hosts: all
      roles:
        - chrony

