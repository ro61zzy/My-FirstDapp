# My-FirstDapp
simple front-end connected to a smart contract:


Use https://remix.ethereum.org/ to complile and deploy your smart contract.
import ethers to use it's methods
use lite-server to automatically run the application on localhost
The script, provider method will connect metamask through window.ethereum which calls the goerli network metamask that is already connected
once your smart contract is deployed, it is given an address and an ABI is created.
your metamask address is used as the signer
the set method writes to the blockchain and the get method, views from the blockchain
