# almaops.monitoring.ct_grafana
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

# Requirements
On target hosts:
- Docker Engine installed
- Python PIP's `docker` module installed

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Example playbook
```
- hosts:
    - servers
  become: true
  collections:
    - almaops.monitoring
  roles:
    - role: ct_grafana   
```

# Contributors
[Valentin Gostev](https://github.com/ussrlongbow)
