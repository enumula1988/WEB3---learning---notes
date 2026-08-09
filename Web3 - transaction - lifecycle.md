# Web3 Transaction Lifecycle

A Web3 transaction is the process of sending an action from a user's wallet to a blockchain and getting it confirmed.

## Transaction Flow

1. User initiates a transaction
   - The user chooses an action such as sending tokens or interacting with a smart contract.

2. Wallet signs the transaction
   - The wallet uses the user's private key to create a digital signature.
   - The private key should never be shared.

3. Transaction is sent to an RPC
   - The wallet sends the signed transaction to an RPC node.
   - The RPC node forwards it to the blockchain network.

4. Network validates the transaction
   - The network checks the signature, account balance, nonce, gas settings, and other rules.

5. Transaction is included in a block
   - A validator or block producer includes the valid transaction in a block.

6. Blockchain confirms the transaction
   - Once the block is accepted by the network, the transaction receives confirmation.

7. Application updates
   - The wallet or dApp reads the updated blockchain state and shows the new balance or result.

## Key Terms

- Wallet: A tool used to manage blockchain accounts and sign transactions.
- Private Key: Secret cryptographic data used to authorize transactions.
- RPC: A service that allows wallets and applications to communicate with a blockchain.
- Gas Fee: The fee paid for processing a transaction on many blockchains.
- Validator: A network participant that helps verify and process transactions.
- Block: A group of transactions recorded together on a blockchain.
- Transaction Hash: A unique identifier used to find and verify a transaction.

## Simple Summary

Wallet → Signature → RPC → Validation → Block → Confirmation → Updated State

## Why This Matters

Understanding the transaction lifecycle helps Web3 users troubleshoot failed transactions, understand gas fees, and know what happens after clicking the "Confirm" button.
