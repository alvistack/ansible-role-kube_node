# Ansible Role for Kubernetes Node

## 4.3.0 - TBC

### Major Changes

  - Template `molecule -s default` with dummy docker driver
  - Support CentOS/RHEL 8
  - Support Ubuntu 20.04
  - Remove Ubuntu 16.04 support
  - Upgrade minimal Molecule support to 3.0.2
  - Migrate role name to lowercase or underline
  - Migrate group name to lowercase or underline
  - Migrate molecule `group_vars` to file
  - Split role as `kube_master` and `kube_node`
  - Support both `docker` and `cri_o`
  - Support both `LocalEtcd` and `ExternalEtcd`

## 4.2.0 - 2020-02-17

  - Ininitial release for Ansible 2.9 or higher
  - Support both Ubuntu 16.04/18.04/19.10 or RHEL/CentOS 7 or openSUSE Leap 15.1
