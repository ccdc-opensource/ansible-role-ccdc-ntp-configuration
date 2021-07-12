# Ansible Role: CCDC NTP configuration

Configures time servers on Linux/Windows/MacOS machines inside CCDC

## Requirements

None.

## Role Variables

None, this is specific to CCDC

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc.ntp_configuration

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas and Florian Piesche, based on existing roles at CCDC, by Jeff Geerling and google searches
