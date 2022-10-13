# staking-contracts

Staking contracts for Exzocoin

## How to start

```shell
$ git clone https://github.com/ExzoNetwork/staking-contracts.git
$ cd staking-contracts
$ npm i
```

### Prepare for use
```shell
$ cp .env.example .env
```
Enter your validator's private key into the `.env` file and save

### Build contracts

```shell
$ npm run build
```

### Run unit tests

```shell
$ npm run test
```

### Deploy contract to Exzocoin

```shell
$ npm run deploy
```

### Stake balance to contract

Please make sure required values are set in .env to use this command

```shell
$ npm run stake
```

### Unstake from contract

```shell
$ npm run unstake
```

### Check current total staked amount and validators in contract

```shell
$ npm run info
```