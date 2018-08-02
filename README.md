# ENS js playground on Tobalaba test network of Energy Web Foundation

For educational purposes.

Used with [Parity client](https://github.com/paritytech/parity-ethereum) version 1.11.6 Beta

### Dependencies

- Connection to Tobalaba. For a tutorial on how to set up a local [Parity client](https://github.com/paritytech/parity-ethereum) and connect to the network, check [here](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/72974337/Install+the+Energy-Web+Client).
- [Parity UI](https://github.com/parity-js/shell) (Helps a lot).
- An account with some test Ethers in it. Use [faucet](http://tobalaba.slock.it/faucet/) to get some ethers.
- Python 3.6 with pip, and Jupyter notebook

### Setup
You need a [Jupyter notebook](http://jupyter.org/install):
```
pip install jupyter
(or pip3 install jupyter)
```
Then you need the [Javascript kernel](https://github.com/n-riesco/ijavascript) fo Jupyter:
```
npm install -g ijavascript
ijsinstall
```
Then

```
git clone https://github.com/ngyam/ewf-ens-js
cd ewf-ens-js
npm install web3@0.20.x
npm install eth-ens-namehash
npm install ethereum-ens
```

### How to use
 1. Make sure your parity client is running and configured to connect to Tobalaba
 2. Open the [Jupyter notebook file](./Tobalaba_ENS.ipynb) and play around.

```
cd ewf-ens-js
jupyter notebook
```

### Resources

[Parity client](https://github.com/paritytech/parity-ethereum)

[ENS official documentation](https://docs.ens.domains/en/latest/)

[ENS Github Repo](https://github.com/ensdomains/ens)

[web3.py documentation](https://web3py.readthedocs.io/en/stable/)  

