# Домашнее задание №17 "Инфраструктура как код" 

Команды для запуска плейбуков:
```
ansible-playbook -i inventory/production playbook.yml --ask-vault-pass
ansible-playbook -i inventory/testing playbook.yml --ask-vault-pass
```

Креды зашифрованы через ansible-vault, поэтому при запуске будет запрошен пароль.

Пароль от vault: `password`.

Креды для доступа к стартовой странице: `admin`:`admin`.
