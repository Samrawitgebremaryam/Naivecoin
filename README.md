# Naivecoin

**Naivecoin** is a simple cryptocurrency project built with TypeScript, aimed at demonstrating the core concepts behind blockchain technology and cryptocurrencies. This project includes the implementation of key features such as transactions, blocks, and peer-to-peer communication.

## Features

- **Blockchain**: A linked list of blocks, each containing a timestamp, transactions, and a cryptographic hash.
- **Transactions**: Implemented using inputs and outputs, ensuring that only valid coins are transferred securely between addresses.
- **Peer-to-Peer (P2P) Network**: Nodes communicate directly with each other to ensure the decentralized nature of the blockchain, allowing for block and transaction synchronization.
  
## Technologies Used

- **TypeScript**: Strongly typed JavaScript used to build the project.
- **Elliptic**: A library used for handling public-key cryptography (ECDSA) and signatures.
- **SHA256**: Used for hashing in the proof-of-work mechanism and to ensure block integrity.
- **WebSockets**: Utilized for peer-to-peer communication, enabling nodes to share blocks and transactions in real time.

## Peer-to-Peer Communication

The P2P network plays a crucial role in maintaining the decentralized nature of Naivecoin. Each node can connect to other nodes (peers) via WebSockets, sharing information such as:

- **New Blocks**: When a block is mined, it is shared with all connected peers to maintain consensus.
- **Transactions**: Valid transactions are propagated across all peers, ensuring they can be included in a block.
- **Peer Discovery**: New peers can be discovered and added dynamically, allowing the network to scale.

## Getting Started

1. Clone the repository and navigate to the project directory.
2. Install the necessary dependencies with `npm install`.
3. Run the project with `npm start`.

Naivecoin demonstrates the key principles behind cryptocurrency and blockchain technology in a simplified manner.

This project is a practical implementation of blockchain and cryptocurrency concepts, built to explore and demonstrate their foundational components.
