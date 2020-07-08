# Ansible Role for Kubernetes Node

## 4.5.0 - TBC

### Major Changes

  - Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

  - Install with static binary archive
  - Default with `crun`
  - Support Fedora 32
  - Support Debian 10
  - Template complex variable with Jinja `namespace()`
  - Replace use of `ansible_hostname` with `inventory_hostname`
  - `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

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
