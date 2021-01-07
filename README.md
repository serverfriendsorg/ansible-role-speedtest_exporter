# Ansible Role: ansible-role-speedtest_exporter

An Ansible Role that installs and configures the Prometheus Gitlab CI pipelines exporter by [Nicolas Lamirault](https://github.com/nlamirault/speedtest_exporter).

## Requirements

- Prometheus instance

## Dependencies

None

## Supported OS

The role currently supports Debian, Ubuntu, CentOS.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

## Example Playbook

    - hosts: prometheus
      roles:
        - serverfriendsorg.speedtest_exporter

## License

GNU General Public License v3.0

## Author Information

This role was created in 2021 by [Steven Conrad Bayer](https://steven.serverfriends.org/).
