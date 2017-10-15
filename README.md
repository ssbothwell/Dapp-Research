# Dapps Research

## Dapp Platforms

## [Ethereum](https://www.ethereum.org/)

> Ethereum is an open-source, public, blockchain-based distributed computing 
platform featuring smart contract (scripting) functionality.[2] It provides
a decentralized Turing-complete virtual machine, the Ethereum Virtual Machine 
(EVM), which can execute scripts using an international network of public nodes.
Ethereum also provides a cryptocurrency token called "ether", which can be 
transferred between accounts and used to compensate participant nodes for 
computations performed.[3] "Gas", an internal transaction pricing mechanism, is
used to mitigate spam and allocate resources on the network.

#### Key Points:
  * Smart Contracts
  * Community Driven Developoment
  * Lots of corporate interest

#### Consensus Mechanisms:
  * Proof of Work
  * Proof of Stake (not yet implemented)

##### Smart Contract Languages:
 * [Solidity](https://solidity.readthedocs.io/en/develop/)

##### Articles/Links:

 * [Ethereum, Gas, Fuel, and Fees](https://media.consensys.net/ethereum-gas-fuel-and-fees-3333e17fe1dc)
 * [Enterprise Ethereum Alliance](https://entethalliance.org/)


## [Neo](https://www.neo.org)

> Neo is a newer chinese alternative to Ethereum. The main selling people being the
ability to write smart contracts in a large number of langauges.  NEO is backed
by the Chinese government. This has become the most important factor for NEO’s
popularity in China, making it China’s first open-source public blockchain
project. NEO is also backed by WINGS, Alibaba, and various Microsoft-like
giants.

### Key Points
  * Smart Contracts
  * Digital Assets
  * Smart Contract Compiler for many languages
  * Premined
  * Funded by Chinese Government

#### Smart Contracts
> The smart contract was first proposed by the cryptographer Nick Szabo in 1994,
> only five years after the creation of the World Wide Web. According to Szabo's
> definition: When a pre-programmed condition is triggered, the smart contract
> will execute the corresponding contract terms. Blockchain technology provides
> us with a decentralized, tamper-resistant, highly reliable system in which
> smart contracts are very useful. NEO has an independent smart contract system:
> NeoContract.
>
> The NeoContract smart contract system is the biggest feature of the seamless
> integration of the existing developer ecosystem. Developers do not need to
> learn a new programming language but use C#, Java and other mainstream
> programming languages in their familiar IDE environments (Visual Studio,
> Eclipse, etc.) for smart contract development, debugging and compilation.
> NEO's Universal Lightweight Virtual Machine, NeoVM, has the advantages of high
> certainty, high concurrency, and high scalability. The NeoContract smart
> contract system will allow millions of developers around the world to quickly
> carry out the development of smart contracts. NeoContract will have a separate
> white paper describing the implementation details.

#### Digital Identity

> Digital identity refers to the identity information of individuals,
> organizations, and other entities that exist in electronic form. The more
> mature digital identity system is based on the PKI (Public Key Infrastructure)
> X.509 standard. In NEO, we will implement a set of X.509 compatible digital
> identity standards. This set of digital identity standards, in addition to
> compatible X.509 level certificate issuance model, will also support Web Of
> Trust point-to-point certificate issuance model. Our verification of identity
> when issuing or using digital identities includes the use of facial features,
> fingerprint, voice, SMS and other multi-factor authentication methods. At the
> same time, we will also use the blockchain to replace the Online Certificate
> Status Protocol (OCSP) to manage and record the X.509 Certificate Revocation
> List (CRL).

#### Digital Assets

> Digital assets are programmable assets that exist in the form of electronic
> data.  With blockchain technology, the digitization of assets can be
> decentralized, trustful, traceable, highly transparent, and free of
> intermediaries. On the NEO blockchain, users are able to register, trade, and
> circulate multiple types of assets. Proving the connection between digital and
> physical assets is possible through digital identity. Assets registered through
> a validated digital identity are protected by law. 
>
> NEO has two forms of digital assets: global assets and contract assets. Global
> assets can be recorded in the system space and can be identified by all smart
> contracts and clients. Contract assets are recorded in the private storage area
> of the smart contract and require a compatible client to recognize them.
> Contract assets can adhere to certain standards in order to achieve
> compatibility with most clients 

### Economic Model

NEO has two native tokens, NEO (abbreviated symbol NEO) and NeoGas (abbreviated
symbol GAS).

NEO, with a total of 100 million tokens, represents the right to manage the
network. Management rights include voting for bookkeeping, NEO network parameter
changes, and so on. The minimum unit of NEO is 1 and tokens cannot be
subdivided.

GAS is the fuel token for the realization of NEO network resource control, with
a maximum total limit of 100 million. The NEO network charges for the operation
and storage of tokens and smart contracts, thereby creating economic incentives
for bookkeepers and preventing the abuse of resources. The minimum unit of GAS
is 0.00000001.

**In the genesis block of the NEO network, 100 million NEOs are generated, GAS has
not yet been generated.** 100 million GAS, corresponding to the 100 million NEO,
will be generated through a decay algorithm in about 22 years time to address
holding NEO. If NEO is transferred to a new address, the subsequent GAS
generated will be credited to the new address.



#### Consensus Mechanisms:
  * Proof of Stake ([Byzantine Fault Tolerant](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance))

#####  Smart Contract Languages:
  * C#/VB.Net
  * F#
  * Java
  * Kotlin
  * C/C++
  * GO
  * JavaScript
  * Python
  * Ruby 

