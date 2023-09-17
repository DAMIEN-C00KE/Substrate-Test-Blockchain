# Substrate-Test-Blockchain
**Custom blockchain created using Substrate SDK**
- This project is not tested or audited, and should not be used for production purposes. It is in its current form, strictly for educational purposes only

*Node template code can be found at:*
- https://github.com/substrate-developer-hub/substrate-node-template
- (Follow the instructions there on running & interacting)

*To interact via front-end, refer to:*
- https://github.com/substrate-developer-hub/substrate-front-end-template

*For monitoring of node metrics, I recommend the Substrate development tutorial to help you get up and running:*
- https://docs.substrate.io/tutorials/build-a-blockchain/monitor-node-metrics/



***Additional Pallets added which are not included in the base substrate-node-template:***
- pallet_identity
- pallet_collective
- pallet_nicks
- custom_pallet (proof_of_existence)

***For overview of additional pallets & dispatchable functions included, please follow the links provided below:***


**pallet_identity**
- https://docs.rs/pallet-identity/latest/pallet_identity/

**pallet_collective**
- https://docs.rs/pallet-collective/latest/pallet_collective/#functions

**pallet_nicks**
- https://docs.rs/pallet-nicks/latest/pallet_nicks/
- https://docs.substrate.io/tutorials/build-application-logic/add-a-pallet/

**custom_pallet (proof_of_existence)**
- https://docs.substrate.io/tutorials/build-application-logic/use-macros-in-a-custom-pallet/
