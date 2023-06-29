# EVM Bytecode Datasets
A collection of EVM smartcontract datasets (in bytecode form). Currently used to develop and benchmark [Gigahorse](https://github.com/nevillegrech/gigahorse-toolchain).

Current datasets:
* __elipmoc-contracts__: The dataset used to evaluate the Elipmoc OOPSLA22 paper. _"A uniform random sample of 5000 unique contracts, first deployed on the main Ethereum network between blocks 12300000 (April 24, 2021) and 13300000 (September 26, 2021)"_
* __solc08-over5k__: A collection of 2000 randomly selected contracts, compiled using `solc 0.8.x` with a bytecode size of over 5 KB.
* __solc08-over10k__: A collection of 2000 randomly selected contracts, compiled using `solc 0.8.x` with a bytecode size of over 10 KB.
* __viair-march23__: A collection of 1022 contracts deployed on the Ethereum mainnet, compiled using the `viaIR` pipeline (after it became stable).
* __viair-june23__: A collection of 1600 contracts deployed on the Ethereum mainnet, compiled using the `viaIR` pipeline (after it became stable).
