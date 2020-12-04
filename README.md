# Ansible Role: jameseck.goenv

A simple role to install goenv.

## Role Variables

Available variables are listed below along with default values (`defaults/main.yml`):

    goenv_version: 1.23.3
  The version of goenv to install

    goenv_dest_dir: ~/.goenv
  The destination to install goenv

    goenv_install_go_versions: [ "1.11.4" ]
  A list of go versions that goenv should install

## Example Playbook

    - hosts: workstation
      roles:
        - jameseck.goenv

## License

MIT / BSD

## Author Information

James Eckersall
