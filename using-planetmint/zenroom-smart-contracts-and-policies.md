# Zenroom Smart Contracts & Policies

[Zenroom](https://zenroom.org/) contracts are part of Planetmint's transactions specification. They can be utilized to attest the computation of certain logic to the network. To do so, a [Zenroom](https://zenroom.org/) contract can be defined with given inputs and the expected outputs of the computation. This will then be submitted to the network, where a node can validate the logic execution and output.

Previously [Zenroom](https://zenroom.org/) was integrated into [cryptoconditions](https://github.com/planetmint/cryptoconditions) to allow for human-readable conditions and fulfilments. These contracts were stateless, which implies that the conditions and fulfilments need to be transacted in the same transaction. However, [PRP-10](https://github.com/planetmint/PRPs/tree/main/10) aims to make stateful smart contracts possible, enabling asynchronous and party-independent contract processing.

As for network-wide or asset-based policies, [PRP-11](https://github.com/planetmint/PRPs/tree/main/11) specifies how these can be implemented and how these can be used to verify a transaction state before it is committed to the network.
