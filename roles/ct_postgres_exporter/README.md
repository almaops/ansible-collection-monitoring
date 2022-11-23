[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](./LICENSE)

# almaops.monitoring.ct_postgres_exporter

# Requirements
This role requires Docker Engine installed on target host.

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Example playbook
```
- hosts:
    - servers
  become: true
  roles:
    - role: almaops.monitoring.ct_postgres_exporter
      ct_postgres_exporter_env_data_source_name: "postgresql://postgres:password@localhost:5432/postgres?sslmode=disable"
      ct_postgres_exporter_bind_addr: "192.168.1.10"
```

# License
[MIT](./LICENSE)

# Contributors
[Valentin Gostev](https://github.com/ussrlongbow)