# Ansible Role: Kafka
This role for install, config kafka cluster

## Requirements

None.

## Role Variables

N/A

## Dependencies

None.

## Example Playbook

    - hosts: all
      gather_facts: yes
      become: true
      serial: 1
      roles:
        - ansible-kafka

## License

MIT

