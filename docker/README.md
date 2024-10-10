# Docker


Устанавливает Docker на разные дистрибутивы Linux.


# Переменные роли
docker_user


# Пример использования
```yaml
- hosts: webservers
  gather_facts: true
  become: true
  roles:
    - docker
```

## TODO
 - Добавить установку под Ubuntu
 - Добавить установку под Debian
