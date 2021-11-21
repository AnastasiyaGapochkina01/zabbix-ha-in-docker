# zabbix-ha-in-docker

```ansible-vault encrypt_string "${your_mysql_root_password}" --name "db_root_password"```

```ansible-vault encrypt_string "${your_db_password}" --name "db_user_password"```

```ansible-playbook -i inventory main.yaml --ask-vault-pass```