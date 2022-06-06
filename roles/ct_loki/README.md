[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](./LICENSE)
# almaops.monitoring.ct_loki

# Requirements
On target hosts:
- Docker Engine installed
- Python PIP's `docker` module installed

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Example playbook
```
# Using collections keyword
- hosts:
    - servers
  become: true
  collections:
    - almaops.monitoring
  roles:
    - role: ct_loki
# Using only roles keyword
- hosts:
    - servers
  become: true
  roles:
    - almaops.monitoring.ct_loki
```

# Contributors
[Valentin Gostev](https://github.com/ussrlongbow)
