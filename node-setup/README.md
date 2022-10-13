---
description: >-
  This section is dedicated to node setup. You can use the all-in-one docker
  solution or install Tendermint, MongoDB, and Planetmint step by step. For more
  advanced users and developers, the second opti
---

# Node Setup

## Deploy a Machine for Your Planetmint Node

The first step is to deploy a machine for your Planetmint node. It might be a virtual machine (VM) or a real machine, for example, an EC2 on AWS or a droplet on Digital Ocean. If you follow this simple deployment template, all your node’s software will run on that one machine. We don’t make any assumptions about where you run the machine. It might be in Azure, AWS, your data centre or a Raspberry Pi.

### IP Addresses

The following instructions assume that all the nodes in the network (including yours) have public IP addresses. A Planetmint network _can_ be run inside a private network using private IP addresses, but we don’t cover that here. Refer to this section for information on private networks.

### Operating System

**Use Ubuntu 18.04 Server or above versions as the operating system.**&#x20;

Similar instructions will work on other versions of Ubuntu and other recent Debian-like Linux distros. You may have to change the names of the packages or install more packages.

### **Network Security Group**

Suppose your machine is in AWS or Azure, _and_ you want users to connect to Planetmint via HTTPS. In this case, you should configure its network security group to allow all incoming and outgoing traffic for:

* TCP on port 22 (SSH)
* TCP on port 80 (HTTP)
* TCP on port 443 (HTTPS)
* Any protocol on port 26656 (Tendermint P2P)

If you don’t care about HTTPS, then forget about port 443, and replace port 80 with port 9984 (the default Planetmint HTTP port).

### Update Your System

SSH into your machine and update all its OS-level packages:&#x20;

`sudo apt update`&#x20;

`sudo apt full-upgrade`

### DNS Setup

* Register a domain name for your Planetmint node, such as `example.com`
* Pick a subdomain of that domain for your Planetmint node, such as `bnode.example.com`
* Create a DNS “A Record” pointing to your chosen subdomain (such as `bnode.example.com`) at your machine’s IP address.
