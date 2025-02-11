# Credentials-On-Chain

# Decentralised Credential Storage
An on-chain immutable data facility for Land titles and Testaments, stored in a secure, permanent format.

## Problem Statement
Conventionally there is an appalling degree of fraud and misrepresentation of information in the Real-estate industry and Testament documentation. Alot of counterfeit credentials have infested the market and individuals have fallen victim of fraud as a result of this unfortunate reality.

Case scenario 1, a person purchases land through a broker and the credential issued to them to ownership validation is counterfeit and unregistered. This can be done to more than two individuals on the same piece of land.

Case scenario 2, a person documents allocation for their wealth upon their death, but its unfavourably modified by those in custody of the documents when the proprieter dies.

## Solution
Minting of all this information on-chain using this infrastructure adds an aspect of transparency and authenticity to the data that is available, since the information is immutably added to a blockchain. Counterfeit documents will be invalidated, since the data is public and can be viewed by any interested party. If the owner can prove ownership through providing the bona fide identity credentials assigned to the data, then disputes of ownership are effectively neutralised.

## Architecture
The dApp has two major components:

Owner credentials : These are factors assigned as indexes to the private keys of the accounts holding the Credential NFT and metadata or the pointer to the Credential storage in an immutable off-chain vault such as IPFS.

Blockchain Account : This is a unique on-chain entity that holds the credential information, NFT of the credential and their metadata

## Business Model
For every post and get request to the blockchain, there is an amount required for transaction to complete. This is cost covers both gas fees and revenue for the service
