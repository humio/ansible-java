[![Build Status](https://cloud.drone.io/api/badges/humio/ansible-java/status.svg)](https://cloud.drone.io/humio/ansible-java)

Ansible Java
=========

This module install Azul Zuul OpenJDK on the host.

Role Variables
--------------

```yaml
java_version: 11.0.1
java_zulu_version: 11.2.3
java_zulu_mirror: https://cdn.azul.com/zulu/bin
java_zulu_build: 1
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: humio.java

License
-------

Apache

Author Information
------------------

If you're having issues with this module please to not hesitate to reach out to us on the #ansible channel on our [Slack community team](https://community.humio.com/).
