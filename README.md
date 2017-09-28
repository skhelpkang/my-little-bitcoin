# my-little-bitcoin

> Sample naive cryptocurrency implementation on JavaScript with UI and simple blockchain explorer

## Features

- Blocks mining with reward and simple POW 
- Create transactions and send amount to address using unspent outputs
- Peer to peer connection, blockchain synchronization
- Multiple wallets, add new wallet
- Demo mode mining to reduce CPU load
- User interface with real time data change
- Status page with latest blocks, current mempool, wallets list with balances
- Chain explorer pages for block, address, transaction
- Descriptive debug messages in develpment mode using debug package
- Server requests logs with winston

## TODO

- Add signature to outputs for transaction, validate signature
- Implement peers blockhains conflict resolution, download only needed part of chain since split
- Store unspent transactions in separate array to reduce CPU usage for larger chain
- Add stats page with charts in UI, use separate chart module to cache chart data on server
- Improve log messages

## Backend setup

``` bash
# install dependencies
yarn

# Start demo node
npm run demo

# Start first node
npm start

# Start second node
npm run start2

# Start third node
npm run start3
```

## Frontend setup

``` bash
# install dependencies
yarn

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run prod

# build for production and view the bundle analyzer report
npm run prod --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```
 