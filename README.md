# ansible-role-apt

Ansible role to manage APT


## Requirements

    None


## Dependencies

    None


## Role Variables

    * apt_cache_valid_time

    Age, in seconds, at which the APT package cache will be updated
    (default: 43200 (12hrs))


## Example playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/apt
    ```


## Supported operating systems

    * Debian (11)
    * Raspbian (11)


## Compliance

    * CIS Debian Linux 11 Benchmark v1.0.0


## License

    BSD-3-Clause
