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

## Example Inventory

```
kafka-1
kafka-2
kafka-3

[kafka_all]
kafka-1
kafka-2
kafka-3
```

## License

MIT

