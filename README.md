# Ansible Role: mysql-deploy

Ansible Role to deploy a MySQL script.


## Requirements

None.

## Role Variables

Available variables are listed below:

    mysql_bind_address: "127.0.0.1"
    mysql_login_user: "root"
    mysql_login_password: "root"
    mysql_db_file: ""

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - apolloclark.mysql-deploy

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Apollo Clark](https://www.apolloclark.com/)
