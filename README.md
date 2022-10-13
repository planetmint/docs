# Planetmint

Meet Planetmint. The metadata blockchain.

It has some database characteristics and some blockchain `properties <properties.html>`\_, including decentralization, immutability and native support for assets.

At a high level, one can communicate with a Planetmint network (set of nodes) using the Planetmint HTTP API, or a wrapper for that API, such as the Planetmint Python Driver. Each Planetmint node runs Planetmint Server and various other software. The `terminology page <terminology.html>`\_ explains some of those terms in more detail.

### Table of Contents

* [Introduction](introduction/)
  * [What is Planetmint?](introduction/about-planetmint.md)
    * [Basic Facts](introduction/about-planetmint.md#basic-facts)
  * [Properties of Planetmint](introduction/properties.md)
  * [Quickstart](introduction/quickstart.md)
    * [IPDB Testnet- Sending Transactions](introduction/quickstart.md#the-ipdb-testnet-sending-transactions)
    * [Installing Planetmint](introduction/quickstart.md#install-planetmint)
* [Using Planetmint](using-planetmint/)
  * [Transactions in Planetmint](using-planetmint/#transactions-in-planetmint)
    * [CREATE Transactions](using-planetmint/#create-transactions)
    * [TRANSFER Transactions](using-planetmint/#transfer-transactions)
    * [Transaction Validity](using-planetmint/#transaction-validity)
  * [A Note on IPLD marshalling and CIDs](using-planetmint/#a-note-on-ipld-marshalling-and-cids)
  * [Contracts & Conditions](using-planetmint/#contracts--conditions)
  * [Zenroom Smart Contracts and Policies](using-planetmint/#zenroom-smart-contracts-and-policies)
* [Networks & Federations](network-setup/)
  * [How to Set Up a Planetmint Network](network-setup/network-setup.md)
  * [Planetmint Networks](network-setup/networks.md)
  * [Kubernetes Deployment Template](network-setup/k8s-deployment-template/)
* [Node setup](node-setup/)
  * [Run Planetmint with all-in-one Docker](broken-reference)
  * [Basic AWS Setup](node-setup/aws-setup.md)
  * [Configuration Settings](broken-reference)
  * [Deploy a Machine for Your Planetmint Node](broken-reference)
  * [Setting up a network of nodes with the Ansible script](broken-reference)
  * [Set Up NGINX](broken-reference)
  * [Set Up Planetmint, Tarantool and Tendermint](broken-reference)
  * [Production Nodes](broken-reference)
    * [Production Node Assumptions](broken-reference)
    * [Production Node Components](broken-reference)
    * [Production Node Requirements](broken-reference)
    * [Production Node Security & Privacy](broken-reference)
    * [Using a Reverse Proxy](broken-reference)
