# How to decrease Substrate Learning Curve

1) Read the Rust Book (1st 14 chapters) https://doc.rust-lang.org/book/title-page.html

2) Read all the documentation of modules in https://github.com/paritytech/substrate/

3) Try meddling with the chain_spec.rs of the node template https://github.com/substrate-developer-hub/substrate-node-template

4) Document all your experimentation with Substrate

5) At the most basic level, the 'node' folder is related to consensus & 'pallet' folder is related to the different functionalities in the substrate-node-template. So any changes regarding consensus are to be made in 'node' folder and any new functionality (for eg Smart Contract). You will have to add it in the 'pallet' folder and then include it in the construct_runtime! macro in the 'runtime' folder.

## Contribution
If you want to contribute to this repository, create a Pull request and I will make sure it is added if it is a valid Point / more detailed way for a specific topic.

## Contact
Discord Server - https://discord.gg/zrxGhrwNs7
