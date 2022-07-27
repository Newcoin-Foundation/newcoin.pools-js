# newcoin.pools-js

JS Library to interact with newcoin.pools smart contract.

## Usage

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/). Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```sh
npm i @newcoin-foundation/newcoin.pools-js
```

### Initialize

Web library can be found in the [dist] folder.

```javascript
// Standard import
const { ActionGenerator, ChainApi } = require("@newcoin-foundation/newcoin.pools-js");

// ES6 import
import { ActionGenerator, ChainApi } from "@newcoin-foundation/newcoin.pools-js"
```

## Documentation

### ChainApi

Uses only native nodeos calls to chain api plugin.

### ActionGenerator

Helper class to construct contract actions which can be signed and pushed to chain with eosjs. 

Detailed information about each action can be found [here](docs/actions.md).