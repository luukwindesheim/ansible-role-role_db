# role_db

Ansible role die MariaDB installeert en een database aanmaakt.

## Variabelen

| Variabele | Standaard | Omschrijving |
|-----------|-----------|--------------|
| db_name   | myapp     | Naam van de database |

## Gebruik

```yaml
- hosts: db
  roles:
    - luukwindesheim.role_db
```
