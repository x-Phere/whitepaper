# Cross-Chain Transaction

Cross-chain transactions involve linking and maintaining the integrity of data between different programs or blockchain networks.&#x20;

Xphere inherently supports transactions between different blockchains without the need for a bridge server. This includes transactions between sub-networks within Xphere and support for transactions between other blockchain networks.&#x20;

Below is an example of a cross-chain transaction realizing the swap of tokens between different blockchains:&#x20;



(1) Chain A: X deposits 50A. Y can convert the deposited amount into an approved transaction by inputting the original value of a specific hash. However, Y only knows the resulting hash value, not the original value. This state can be canceled after 10 minutes.&#x20;

(2) Chain B: Y deposits 100B. By inputting the original value of the hash generated in step (1), X can convert the deposited amount into an approved transaction. Since Y knows the hash result from Chain A, it's possible to set up a contract on Chain B based on the original value from Chain A, even on a different chain. This state can be canceled after 5 minutes.&#x20;

(3) Chain B: X inputs the original value of the hash and completes the transaction from step (2).&#x20;

(4) Chain A: Since the transaction from step (2) is completed, Y can now know the original value of the hash generated in step (1).&#x20;



By combining receipts with cross-chain transaction technology, proof generation for program execution as well as data queries can be achieved. Additionally, it's possible to include separate executable binary code in blocks rather than contract code. This means that, depending on the design, all network participants can become essential elements of distributed computing.



<figure><img src="../.gitbook/assets/Group 48096351.png" alt=""><figcaption><p>Cross-Chain Transaction Structure Diagram</p></figcaption></figure>



<figure><img src="../.gitbook/assets/Group 48096352.png" alt=""><figcaption><p>Cross-Chain Transaction Structure Diagram</p></figcaption></figure>



### Random Number

In a blockchain network, all participants must compute the same result, making traditional random number systems unsuitable. The Xphere blockchain network provides a "Random Number" variable determined by the block hash at the moment the block is created within the contract. In the Xphere-based network, the block hash value of the main chain is nearly unpredictable, thus providing complete randomness within the maximum computation limit of the block hash.



### Gas Price

The network fee per transaction in Xphere is 1X10-6 XP (Xphere, XP). The Xphere blockchain network determines the gas fee for each block. Gas fees are paid from the sender's account for transactions submitted from that account. Additionally, transactions are recorded in a block, which applies to all blockchain nodes. In summary, transaction fees are deducted from the sender's or fee payer's account. Unlike Ethereum, Xphere uses a fixed gas fee per transaction. This gas fee policy provides users with stable service. However, dynamic gas fee policies may be applied in some cases to limit network abuse or storage abuse. This may not target simple cryptocurrency transfers but could involve the creation, transfer, or storage of large amounts of data such as NFTs. Such dynamic gas fee algorithms mean that if the gas used exceeds the base gas, the base fee may increase, and vice versa. This is closely related to the number of transactions and processes in the network. To prevent fees from increasing or decreasing infinitely, there may be upper and lower limits on the base fee. Additionally, adjustments may be made to the limits and fluctuations for gas to prevent drastic changes in the base fee. These values may be subject to change based on governance.









