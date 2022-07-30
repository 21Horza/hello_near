Hello, NEAR
==================

This APP is designed as a demonstration of basic greeting smart contract.
Demo is available at https://21horza.github.io/hello_near/


===========

<img width="724" alt="Screenshot 2022-07-30 at 17 56 35" src="https://user-images.githubusercontent.com/81642088/181905302-947cec64-80c9-457b-ad56-39feff001ef9.png">


Exploring The Code
==================

1. The "backend" code lives in the `/contract` folder. See the README there for
   more info.
2. The frontend code lives in the `/src` folder. `/src/index.html` is a great
   place to start exploring. Note that it loads in `/src/index.js`, where you
   can learn how the frontend connects to the NEAR blockchain.
3. Tests: there are different kinds of tests for the frontend and the smart
   contract. See `contract/README` for info about how it's tested. The frontend
   code gets tested with [jest]. You can run both of these at once with `yarn
   run test`.
