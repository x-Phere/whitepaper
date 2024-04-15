# Xphere Smart Contract

The Xphere smart contract is a program that executes all types of code that interact with the Xphere blockchain, including business logic, games, libraries, and token transfers. When the conditions of a smart contract are met, the contract is executed immediately. The conditions within smart contracts are written in programming languages. The data of the contract is stored as transaction and state data. Xphere will provide developers with the most familiar development environment to support Ethereum DApp developers in easily migrating their work to Xphere. Long-term, Xphere plans to accommodate smart contracts written in various programming languages. Therefore, we will continue to support a wider range of developers and enable them to develop in their most familiar environments.



### Xphere Smart Contract Application

Satoshi Nakamoto demonstrated that with the combination of blockchain and proof of work, it is possible to implement a fully functional electronic cash system without relying on a trusted third party. Vitalik Buterin introduced the concept of 'smart contracts', which are blockchain data containing executable code, as an attempt to apply blockchain technology to areas beyond currency. Network users can call the code that manages the code to register or modify new code, and users can call the registered code to use new code deployed by themselves or others. For this purpose, the types of data stored in the blockchain are divided into transactions and states, and the final state of the blockchain network can be understood by sequentially calculating transactions. The system provides a contract called the VM (Virtual Machine) that manages codes such as creation, registration, modification, and deletion. Other common service concepts are designed as contracts and integrated into block data. The virtual machine specifies a state data area that code registrants and users can access and manipulate to prevent incorrect code execution and restrict code execution time to prevent indefinite code execution.



<figure><img src="../.gitbook/assets/Group 48096328.png" alt=""><figcaption><p>Xphere Smart Contract Structure Diagram</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Group 48096329.png" alt=""><figcaption><p>Xphere Smart Contract Structure Diagram</p></figcaption></figure>



### Partial Data Storage

As transactions are processed rapidly, the rate of increase in total data capacity also sharply increases. In traditional blockchains, this isn't a major issue due to hardware performance improving according to Moore's Law. However, in ultra-fast blockchain networks like Xphere, the total data capacity exceeds the limit of what a single computer can store.  &#x20;

#### Maximizing Storage Efficiency with Optimized Merkle Tree Method

Network participants separate blockchain data into data stored publicly and data stored individually. Participants then store only the data assigned to their peer address and delete the rest. Peer addresses are typically randomly determined, distributing the data evenly as the network grows. Additionally, participants who want the blockchain network to remain intact will build multiple nodes to store the entire data. As described, blockchain data is divided into transaction data and state data. Since block data includes transaction data, it can be organized using a Merkle tree to classify common storage and individual storage sections. State data is structured using a Merkle tree with key-value hash tables to classify common storage and individual storage sections. If data is divided into too many parts, the peer holding that data cannot be immediately identified. In such cases, peers storing the data are found using a method similar to finding IP addresses.









