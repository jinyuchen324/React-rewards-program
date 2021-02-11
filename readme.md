
# Transaction Data Generation

Running `npm run generate` will call this file `./src/api/generate.js` and you can specifiy the number of transactions with this function `generateTransactions`, the default is 200. That command will generate/scaffold the transaction data in `./src/api/data/transactionData.json` to make playing with data easier.

# Components

I opted out using any third party component libraries like material UI

# Tests

Tests are located in `./src/tests` to help test calculating points. To run a test run `npm run test`.

# Deployment

* `npm run build:deploy`

# Node version used

v8.17.0