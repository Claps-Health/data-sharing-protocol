# Claps Health Data Sharing Protocol
## Introduction
Claps Health Data Sharing Protocol (Data Authorize Control) is a proof of concept for a secure and decentralized protocol for managing health data consent, access control, and data auditing. The protocol is designed to enable individuals to securely share their health data with trusted parties, such as healthcare providers, researchers, or family members.

This proof of concept demonstrates the basic functionality of the Claps Health Data Sharing Protocol for Data Authorize Control, including one-to-many data sharing, access control, and data auditing.

The DataAnchor smart contract is a component of the Claps Health Data Sharing Protocol  that is used to store and manage health data hashes. Data hashes are used to verify the integrity of data that is stored on the database.

## Market problems of data sharing
Data sharing in healthcare has been a longstanding challenge due to concerns around data privacy and security. Patients often lack control over their health data and face challenges when trying to access or share their information with different healthcare providers or sharing data with patient groups.

## Proof of Concept
The protocol consists of two smart contracts: DataAnchorl and DataAuthorize.

DataAnchor is a smart contract that provides data integrity by storing the hash codes of health data on the blockchain. The contract ensures that the data cannot be modified or tampered with without being detected.

DataAuthorize is a smart contract that enables patients to control the sharing of their health data. The contract provides a secure method for patients to grant or revoke access to their data, ensuring that their privacy is maintained.

## Installation

To use the DataAuthorize and DataAnchor smart contracts, you will need to have an Ethereum-compatible blockchain network and a compatible wallet. You can deploy the contracts using Solidity development environment. Once deployed, you can interact with the contracts using their public methods.

## Usage
To use the Claps Health Data Sharing Protocol, you will need to have some knowledge of Solidity and smart contract development. You can import the DataAnchor and DataAuthorize contracts into your own contracts and use them to manage data sharing.

For more details, please see the code notes of each module and test case.

## Features
The Claps Health Data Sharing Protocol provides the following features:

- Support users to sign messages on client side and verified by the data receivers

- One-to-many data sharing, allowing users to engage with multiple patient groups, health practitioners, or healthcare service providers, and share data with many parties

- Access control, allowing users to manage lists for data sharing

- Data auditing, allowing parties such as researchers to audit data for AI training, authentic data checks, and compliance with regulations

- Compatibility: the protocol is built on Solidity, making it compatible with Ethereum-based EVM

## Limitations and Future Development
This proof of concept has the following limitations:

The current proof of concept for Claps Health Data Sharing Protocol (Data Authorize Control) does not include data sharing encryption/decryption. Future development for this protocol could include the addition of data sharing encryption/decryption using the end-to-end data encryption to secure NOT-ON-CHAIN health data. Or other secure encryption methods.

Limited scalability due to current limitations of blockchain technology.

## Claims

The Claps Health Data Sharing Protocol aims to provide patients with greater control over their health data, including the right to delete their data. To comply with regulations such as HIPAA and GDPR, health data should not be stored directly on the blockchain. 

Claps Health is committed to developing a platform that is secure, easy to use, and compliant with applicable regulations.

## Contributing

We welcome contributions to the Claps Health Data Sharing Protocol. If you have any suggestions or would like to contribute to the development of the protocol, please open an issue or submit a pull request on our GitHub repository.

## License
The Claps Health Data Sharing Protocol is licensed under the MIT License.
