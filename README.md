This Smart Contract (ChainCode) is purposefully crafted to oversee the comprehensive management of patient records stemming from their activities, while simultaneously orchestrating the
establishment of references to these activities within the domain of the private blockchain ledger(Hyperledger Fabric). Serving as an intermediary, this ChainCode bridges the patient data residing within the
IPFS with the maintained blockchain ledger residing within the scope of the private medical network. Its fundamental mission resides in the assurance of secure access to patient data,
firmly upheld within the secure embrace of the private blockchain network.

The role of the ChainCode is of significance as it serves as the governing mechanism for the business logic within the network. Specifically, our ChainCode, named IPFS, plays a 
crucial role in linking a patient’s activities within the private medical network to their stored medical information on IPFS. The IPFS ChainCode is packaged as a Docker container for
convenient installation on the network’s peers.
The ChainCode deployment comprises three stages: Discovery, Approval, and Commitment. In Discovery, the ChainCode package’s adherence to formatting standards is verified for suitability
on network peers. Approval involves medical institutions endorsing and validating the ChainCode definition. Following approval, the ChainCode is installed on network peers in the Commitment
stage, finalizing the deployment process.
