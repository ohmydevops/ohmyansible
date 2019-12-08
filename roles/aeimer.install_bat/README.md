# Ansible role to install bat
Installs [bat](https://github.com/sharkdp/bat) (a cat replacement) via [Ansible](https://ansible.com).

[![Build Status](https://travis-ci.org/aeimer/ansible-install-bat.svg?branch=master)](https://travis-ci.org/aeimer/ansible-install-bat)

---

- [Ansible Galaxy: aeimer.install_bat](https://galaxy.ansible.com/aeimer/install_bat)
- [Github: aeimer/ansible-install-bat](https://github.com/aeimer/ansible-install-bat)

---

If there are any issues, it would be kind if you open a pull-request or open an issue, so we can fix the things.

<!--
## Variables
| Name | Default Value | Description |
| ---- | ------------- | ----------- |
|  |  |  |
-->

## Example Playbook
To install the role:
```bash
ansible-galaxy install aeimer.install_bat
```

To run the role in a playbook:
```yaml
- host: localhost
  roles:
    - aeimer.install_bat
```

## Known Issues
- This is only tested with Ubuntu
