# vagrant-libvirt-k8s

DO SMART WORK RATHER THAN HARD WORK!

Vagrant for kubernetes on libvirt

This module requires [Vagrant](https://www.vagrantup.com/docs/installation) to pre-installed.
And any virtual environment, defualt can use [libvirt](https://libvirt.org/)

## Basic usage
Very first `cd` to path where `Vagrantfile` exists, and open `Vagrantfile` file to update setting before spin up cluster.

### Command line
To start kubernetes cluster please follow below instructions:

```bash
vagrant up k8s-master && vagrant up
```
