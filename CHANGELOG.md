Changelog
=========

[1.2.4] - 2022-05-06
--------------------

### New Features

- none

### Bug Fixes

- none

### Other Changes

- bump tox-lsr version to 2.11.0; remove py37; add py310

[1.2.3] - 2022-04-19
--------------------

### New Features

- support gather\_facts: false; support setup-snapshot.yml

### Bug Fixes

- none

### Other Changes

- none

[1.2.2] - 2022-03-31
--------------------

### New Features

- none

### Bug Fixes

- network-flush: reset autoconnect-priority to zero

### Other Changes

- none

[1.2.1] - 2022-03-29
--------------------

### New Features

- Add dracut module for disabling autoconnect within initrd

### Bug Fixes

- none

### Other Changes

- bump tox-lsr version to 2.10.1

[1.2.0] - 2022-01-13
--------------------

### New Features

- none

### Bug Fixes

- Add network flushing before setting up network

### Other Changes

- none

[1.1.2] - 2022-01-10
--------------------

### New Features

- none

### Bug Fixes

- none

### Other Changes

- bump tox-lsr version to 2.8.3
- change recursive role symlink to individual role dir symlinks

[1.1.1] - 2021-11-08
--------------------

### New Features

- support python 39, ansible-core 2.12, ansible-plugin-scan
- add regenerate-all to the dracut command 

### Bug Fixes

- none

### Other Changes

- update tox-lsr version to 2.7.1
- make role work with ansible-core-2.11 ansible-lint and ansible-test
- use tox-lsr version 2.5.1

[1.1.0] - 2021-08-10
--------------------

### New Features

- Drop support for Ansible 2.8 by bumping the Ansible version to 2.9

### Bug Fixes

- none

### Other Changes

- none

[1.0.4] - 2021-06-08
--------------------

### New Features

- none

### Bug Fixes

- fix python black formatting errors

### Other Changes

- none

[1.0.3] - 2021-04-08
--------------------

### New Features

- none

### Bug Fixes

- Fix issues found by ansible-test and linters - enable all tests on all repos - remove suppressions
- Fix ansible-test errors

### Other Changes

- Remove python-26 environment from tox testing
- README.md - Adding a blank line after nbde\_client\_bindings
- update to tox-lsr 2.4.0 - add support for ansible-test sanity with docker
- Increase memory of tests
- CI: Add support for RHEL-9

[1.0.2] - 2021-02-11
--------------------

### New Features

- Add centos8

### Bug Fixes

- Fix centos6 repos; use standard centos images

### Other Changes

- use tox-lsr 2.2.0
- use molecule v3, drop v2
- support jinja 2.7
- remove ansible 2.7 support from molecule
- use tox for ansible-lint instead of molecule
- use new tox-lsr plugin
- use github actions instead of travis

[1.0.1] - 2020-10-31
--------------------

### New Features

- none

### Bug Fixes

- none

### Other Changes

- meta/main.yml: CI add support for Fedora 33
- lock ansible-lint version at 4.3.5; suppress role name lint warning
- sync collections related changes from template to nbde\_client role

[1.0.0] - 2020-08-13
--------------------

### Initial Release