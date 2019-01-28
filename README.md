# OpenStack Ansible openstack_deploy

My personal OpenStack Ansible configurations.

This is a fully operational OSA Rocky deployment.

It works very well with Ubuntu MaaS!

## Features

Nova settings for both KVM and LXD Hypervisors.

Cinder Volumes as a Containers (since I'm not using LVM2 / iSCSI).

All Neutron agents are bare metal and runs at the KVM Compute nodes.

For now, only Linux Bridges are supported but, OpenvSwitch is working in a different environment and, OVN will soon be added! As well as OVS with DPDK.
