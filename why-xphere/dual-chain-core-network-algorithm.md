# Dual Chain Core Network Algorithm

The Dual Chain Core Network Algorithm of Xphere provides an innovative approach to overcoming the limitations of traditional proof-of-work (PoW) based blockchain systems. Conventional systems relying solely on validators have struggled to ensure transaction finality within a short period, leading to several issues. Particularly, the heavy reliance on validators poses risks, as there is a possibility of recreating all past to present block data and overwriting it with double signatures.



### Swift Transaction Registration with Dual Chain Application

The algorithmic approach of relying solely on validators presents significant risks. Xphere addresses this by introducing a Dual Chain system, which combines proof-of-work with a unique algorithm. This system offers both swift transaction processing and high security simultaneously. The Dual Chain comprises the Resource Chain (Resource Chain) for selecting validators via proof-of-work and the Main Chain (Main Chain) for processing regular transactions using a validation algorithm. Users who successfully mine receive minor incentives and are elected as validators for the next block. To obtain greater incentives, they must fully process regular transactions and generate the main block. Network participants synchronize the Resource Chain based on the longest resource block and synchronize the Main Chain based on the block hash recorded in the Resource Chain. Unrecorded Main Chain block data in the Resource Chain is considered provisional until observed by a malicious user in real-time, ensuring swift transaction registration completion.



### Dual Chain Block Generation Process

1. Mining Incentives and Validator Selection: Users who succeed in mining receive incentives and are selected as validators for the next block. This encourages network participation and plays a vital role in verifying transaction accuracy. &#x20;
2. Transaction Processing and Main Block Generation: Validators process transactions occurring in the network and create the main block containing them. They can acquire greater incentives during this process. &#x20;
3. Synchronization of Resource Chain and Main Chain: Network participants synchronize the Resource Chain based on the longest resource block, which serves as the basis for synchronizing the Main Chain. This ensures consistency between the two major chains and enhances the completeness of swift transaction registration through the handling of temporary block data. &#x20;
4. Handling of Temporary Block Data: Block data not recorded in the Main Chain is temporarily considered provisional, ensuring the completeness of swift transaction registration unless a separate branch is observed. &#x20;
5. Synchronization and Consensus Mechanism: ChainMaker manages synchronization with other nodes in the network and maintains network consistency through the consensus process when necessary.









