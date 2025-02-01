## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

<<<<<<< HEAD
```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
=======
> :warning: **Make sure to use the correct commit when deploying the contracts.** Any change (even comments) within the contract files will result in different addresses. The tagged versions that are used by the Safe team can be found in the [releases](https://github.com/safe-global/safe-smart-account/releases).

> **Current version:** The latest release is [v1.4.1-3](https://github.com/safe-global/safe-smart-account/tree/v1.4.1-3) on the commit [21dc824](https://github.com/safe-global/safe-smart-account/commit/21dc82410445637820f600c7399a804ad55841d5)

This will deploy the contracts deterministically and verify the contracts on etherscan using [Solidity 0.7.6](https://github.com/ethereum/solidity/releases/tag/v0.7.6) by default.

Preparation:
- Set `MNEMONIC` in `.env`
- Set `INFURA_KEY` in `.env`
- For zkSync, set `ZKSYNC_DEPLOYER_PK` in `.env`

```bash
npm run deploy-all <network>
>>>>>>> 7867baf1f967e98d05e9693b0c97e74d8df866bd
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
<<<<<<< HEAD
=======

This command will upload the contract source to Etherscan
```bash
npx hardhat --network <network> etherscan-verify
```

Documentation
-------------
- [Safe developer portal](http://docs.safe.global)
- [Error codes](docs/error_codes.md)
- [Coding guidelines](docs/guidelines.md)

Audits/ Formal Verification
---------
- [for Version 1.4.0/1.4.1 by Ackee Blockchain](docs/audit_1_4_0.md)
- [for Version 1.3.0 by G0 Group](docs/audit_1_3_0.md)
- [for Version 1.2.0 by G0 Group](docs/audit_1_2_0.md)
- [for Version 1.1.1 by G0 Group](docs/audit_1_1_1.md)
- [for Version 1.0.0 by Runtime Verification](docs/rv_1_0_0.md)
- [for Version 0.0.1 by Alexey Akhunov](docs/alexey_audit.md)

Security and Liability
----------------------
All contracts are WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

License
-------
All smart contracts are released under LGPL-3.0
>>>>>>> 7867baf1f967e98d05e9693b0c97e74d8df866bd
