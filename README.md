# Ethereum ENS tutorial and playground with JavaScript and web3.js

For educational purposes.

Used with [Parity client](https://github.com/paritytech/parity-ethereum) version 1.11.6 Beta

### Dependencies

- Connection to Tobalaba. For a tutorial on how to set up a local [Parity client](https://github.com/paritytech/parity-ethereum) and connect to the network, check [here](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/72974337/Install+the+Energy-Web+Client).
- [Parity UI](https://github.com/parity-js/shell) (Helps a lot).
- An account with some test Ethers in it. You can use ParityUI for this purpose, then navigate to the [faucet](http://tobalaba.slock.it/faucet/) to get some ethers.
- Python 3.6 with pip, and Jupyter notebook

### Setup
You need a [Jupyter notebook](http://jupyter.org/install):
```
pip install jupyter
(or pip3 install jupyter)
```
Then you need the [Javascript (node) kernel](https://github.com/n-riesco/ijavascript) fo Jupyter:
```
npm install -g ijavascript
ijsinstall
```
Then

```
git clone https://github.com/ngyam/tutorial-ens-js.git
cd tutorial-ens-js
npm install web3@0.20.x
npm install eth-ens-namehash
npm install ethereum-ens
```

### How to use
 1. Make sure your parity client is running and configured to connect to Tobalaba
 2. Open the [Jupyter notebook file](./ENSTutorialJs.ipynb) and play around.

```
cd tutorial-ens-js
jupyter notebook
```

### Resources

[Energy Web Foundation](https://energyweb.org/)

[Parity client](https://github.com/paritytech/parity-ethereum)

[ENS official documentation](https://docs.ens.domains/en/latest/)

[ENS Github Repo](https://github.com/ensdomains/ens)

[web3.js documentation](https://github.com/ethereum/wiki/wiki/JavaScript-API)  

