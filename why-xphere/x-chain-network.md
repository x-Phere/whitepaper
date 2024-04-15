# X-Chain Network

## X-Chain Network

Traditional blockchain structures, which rely solely on validators, have posed significant burdens on the distributed processing speed of blockchains. Additionally, the integration of applications within a blockchain has often compromised the efficiency of service provision. To address these challenges, the Xphere blockchain is divided into three logically distinct sub-chain networks based on roles, optimizing system operations.





1.  **Resource Chain Network**&#x20;

    The Resource Chain plays a crucial role in pre-selecting validators through proof-of-work. Nodes that successfully mine receive minor incentives and are subsequently selected as the next validators. These incentives, referred to as "resources," are converted into Xphere (XP) coins through a refinement process. Operating separately from the main chain, the Resource Chain streamlines block creation and transaction settlement times by segregating the mining, validator selection, and block generation processes.
2.  **Main Chain Network**&#x20;

    The Main Chain Network serves as the primary blockchain for verifying and executing submitted transactions. It is responsible for block generation and propagation. Pre-selected validators create blocks and finalize transactions. Through a separate hypothesis acceptance algorithm, validators who ultimately generate blocks can acquire additional resources beyond those mined. Network participants synchronize the Resource Chain based on the longest resource block and synchronize the Main Chain based on the block hash recorded in the Resource Chain. Unrecorded Main Chain block data in the Resource Chain is considered provisional until observed by a malicious participant in real-time, at which point it is confirmed as the final block. This process ensures both swift transaction finalization and security.
3.  **Service Chain Network**&#x20;

    The Service Chain Network comprises auxiliary blockchains operated independently by decentralized application (dApp) providers, forming a subset of the Xphere network. Connected to the Main Chain Network through nodes that generate transactions and process data requests, these chains enable blockchain applications to operate autonomously. Businesses deploying blockchain applications can establish their own execution environment with high transaction processing speeds (TPS) and the ability to modify network policies. This provides for stable and fast transaction processing capabilities.



<figure><img src="../.gitbook/assets/Group 48096350.png" alt=""><figcaption><p>X-Chain Network Structure Diagram</p></figcaption></figure>









