# Smart Contracts Repository Template

![GitHub](https://img.shields.io/github/license/iis-vallauri-fossano/esercitazione-smart-contracts-2324?style=flat-square)

The Smart Contracts Development kit repository, based on Waffle, Typescript, used to create decentralized projects from a solid base.

This template includes an Example ERC20 implementation with tests.

# Usage

First of all you need to install the dependencies

``` bash
yarn install
```

Then you can add your solidity smart contracts to the [`contracts`](./contracts) directory
and the contract tests to the [`test`](./test) directory.

Finally, you can build your contracts using

``` bash
yarn build
```

and you can test them using

``` bash
yarn test
```

Finally, you can create a flatten version of all the contracts using the command

``` bash
yarn flatten
```

You will be able to use this flatten file to deploy your contract using Remix or
verify your contract using Etherscan or BSCscan.

This project is powered by [`waffle`](https://getwaffle.io) and [`Typescript`](https://www.typescriptlang.org).

Please, see the details of the scripts in [`package.json` file](package.json).
