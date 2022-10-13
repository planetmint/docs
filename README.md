
# Planetmint

Meet Planetmint. The metadata blockchain.

It has some database characteristics and some blockchain `properties <properties.html>`_,
including decentralization, immutability and native support for assets.

At a high level, one can communicate with a Planetmint network (set of nodes) using the Planetmint HTTP API, or a wrapper for that API, such as the Planetmint Python Driver. Each Planetmint node runs Planetmint Server and various other software. The `terminology page <terminology.html>`_ explains some of those terms in more detail.


### Table of Contents

* [Introduction](introduction/README.md)
  * [What is Planetmint?](introduction/about-planetmint.md)
    * [Basic Facts](introduction/about-planetmint.md#basic-facts)
  * [Properties of Planetmint](introduction/properties.md)
  * [Quickstart](introduction/quickstart.md)
    * [IPDB Testnet- Sending Transactions](introduction/quickstart.md#the-ipdb-testnet-sending-transactions)
    * [Installing Planetmint](introduction/quickstart.md#install-planetmint)
* [Using Planetmint](using-planetmint/README.md)
  * [Transactions in Planetmint](using-planetmint/README.md#transactions-in-planetmint)
    * [CREATE Transactions](using-planetmint/README.md#create-transactions)
    * [TRANSFER Transactions](using-planetmint/README.md#transfer-transactions)
    * [Transaction Validity](using-planetmint/README.md#transaction-validity)
  * [A Note on IPLD marshalling and CIDs](using-planetmint/README.md#a-note-on-ipld-marshalling-and-cids)
  * [Contracts & Conditions](using-planetmint/README.md#contracts--conditions)
  * [Zenroom Smart Contracts and Policies](using-planetmint/README.md#zenroom-smart-contracts-and-policies)
* [Networks & Federations](network-setup/README.md)
  * [How to Set Up a Planetmint Network](network-setup/network-setup.md)
  * [Planetmint Networks](network-setup/networks.md)
  * [Kubernetes Deployment Template](network-setup/k8s-deployment-template/README.md)
* [Node setup](node-setup/README.md)
  * [Run Planetmint with all-in-one Docker](node-setup/all-in-one-planetmint.md)
  * [Basic AWS Setup](node-setup/aws-setup.md)
  * [Configuration Settings](node-setup/configuration.md)
  * [Deploy a Machine for Your Planetmint Node](node-setup/deploy-a-machine.md)
  * [Setting up a network of nodes with the Ansible script](node-setup/planetmint-node-ansible.md)
  * [Set Up NGINX](node-setup/set-up-nginx.md)
  * [Set Up Planetmint, Tarantool and Tendermint](node-setup/set-up-node-software.md)
  * [Production Nodes](node-setup/production-node/README.md)
    * [Production Node Assumptions](node-setup/production-node/node-assumptions.md)
    * [Production Node Components](node-setup/production-node/node-components.md)
    * [Production Node Requirements](node-setup/production-node/node-requirements.md)
    * [Production Node Security & Privacy](node-setup/production-node/node-security-and-privacy.md)
    * [Using a Reverse Proxy](node-setup/production-node/reverse-proxy-notes.md)
