@0xsequence/erc20-meta-token
============================

Allows any ERC-20 token to be wrapped inside of an ERC-1155 contract, and thereby
allows an ERC-20 token to function as an ERC-1155 contract.

For more information see, [github.com/0xsequence/erc-1155](https://github.com/0xsequence/erc20-meta-token)


## Getting started

### Install

`npm install @0xsequence/erc20-meta-token` or `yarn add @0xsequence/erc20-meta-token`

### Usage from Solidity

```solidity
pragma solidity ^0.7.4;

import '@0xsequence/erc20-meta-token/contracts/wrapper/ERC20Wrapper.sol';

contract MyERC20MetaToken is ERC20Wrapper {
  ...
}
```

## NOTES

`@0xsequence/erc20-meta-token` includes the following files in its package distribution:

* `artifacts` -- hardhat output of contract compilation
* `typings` -- ethers v5 typings for easier interfacing with the contract abis


## LICENSE

Copyright (c) 2017-present [Horizon Blockchain Games Inc](https://horizon.io).

Licensed under [Apache-2.0](https://github.com/0xsequence/erc-1155/blob/master/LICENSE)