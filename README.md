# test_ufity_token
Test Ufity token smart contract

## Features
- ERC20 compliant
- issuer can distribute daily rewards
- issuer can withdraw funds to an external client's wallet

## TODO

- Add SafeMath library
- Put private to internal variables
- Put constant/view on methods that do not modify the blockchain
- Allow to execute the daily token distribution only after X blocks, so that the distribution can happend only (more or less) once per day
- ...

## Test

To test the smart contract, deploy it on the `Ropsten Test Net` via [remix.ethereum.org](https://remix.ethereum.org/ "Remix")
