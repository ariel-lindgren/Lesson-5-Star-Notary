# CryptoStar Dapp

This project contains the code for a Smart Contract compliant with the ERC-721 Token to manage non-fungible tokens for the CryptoStar DAPP.

## Getting Started

### Prerequisites

You'll need Node.js (v 8.12), npm, Truffle (v 5.0.3) and OpenZeppelin (v 2.1.2) installed in order to run this project.

You'll also need the MetaMask extension in order to execute the web based DAPP.

*Token Name:* Lindgren Udacity Star Token
*Token Symbol:* LUST

Currently there is a instance of the Smart Contract deployed on the Rinkby network at the following address: [0xe0895abc79b6dcd63760e26d1cf143a732b40eaf](https://rinkeby.etherscan.io/address/0xe0895abc79b6dcd63760e26d1cf143a732b40eaf)

### Installing

Clone the git repository and use the npm install command to install the package dependencies.

```bash
npm install -g truffle
npm i
```

## Executing on the local machine

After downloading and installing the necessary packages, run truffle on development mode:

```bash
truffle develop
```

After the Truffle console is open, execute the following commands:

```bash
> compile
> migrate --reset
> test
```

All tests should pass.

## Deploying to the Rinkey Network

To deploy the contract to the Rinkeby network, execute the following command:

```bash
truffle deploy --network rinkeby --reset
```

## Running the Front-end Application

On the terminal, change into the "app" folder, verify that you have all the required packages by running:

```bash
npm install
```

After that, run:

```bash
npm run dev
```

and access the application through the URL supplied in the console.

## Authors

* **Ariel Lindgren**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* The folks at Udacity that provided this great content!
