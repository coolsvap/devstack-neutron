devstack-neutron
================
Devstack and Neutron localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

Clone devstack-neutron
```
$git clone https://github.com/svashu/devstack-neutron.git
```

Copy localrc from devstack-neutron to devstack
```
$ cp devstack-neutron/localrc devstack

```

Modify the devstack/localrc for IP and password modifications

Deploy your Devstack

```
$cd devstack && ./stack.sh
```

