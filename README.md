[LINT](https://github.com/buissetemmanuel/ansible-inventory-kafka/actions/workflows/lint.yml/badge.svg) ![RELEASE](https://github.com/buissetemmanuel/ansible-inventory-kafka/actions/workflows/release.yml/badge.svg)

INVENTORY KAFKA to consume [ANSIBLE ROLE KAFKA](https://github.com/buissetemmanuel/ansible-role-kafka.git)
=========

**KAFKA** installation from scratch in **KRAFT** mode.

Goal
--------------

- manage packages if needed
- manage users if needed
- manage systems if needed
- 2 users include group and 1 group to access logs
- owner of files is not the user that manage systemd service
- manage 1 server or X server

Requirements
--------------
![ansible](https://img.shields.io/badge/ansible-2.12.3-green.svg)
![molecule](https://img.shields.io/badge/molecule-4.0.4-green.svg)
![vagrant](https://img.shields.io/badge/vagrant-2.0.0-green.svg)

TODO
-------
- try to find a solution because [Github actions runner nested virtualization is not working at all](https://github.com/actions/runner-images/discussions/7191), so it's not possible to test in local and to have the same code for pipeline. Maybe try Travis.

License
-------

[mit license]: https://img.shields.io/badge/License-MIT-blue.svg
[![mit license]](LICENSE)

Author Information
------------------

[email]: https://img.shields.io/badge/@-emmanuel@buisset.ch-orange.svg
[![email]](mailto:emmanue@buisset.ch)
