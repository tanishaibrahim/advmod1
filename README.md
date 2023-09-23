# Local Avalanche Subnet

I have created a local Avalanche subnet and I have deployed my contract to my subnet.

## Description

In my project, I have deployed the solidity smart contract which contains two contracts - ERC20 and Vault to my subnet that I created using Avalanche CLI locally . I created my own token called 'TAN' with chain id-1111. By connecting my metamask to remix , I was able to deploy my contract.
 ## Getting Started
 
 ### Executing the code
 
* Firstly copy and paste the smart contract into your remix and then change the environment in deploy to injected provider and connect your metamask account.

* Next, install Avalanche CLI and export path by pasting these commands into your linux terminal -
  ```
  curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s
  ```
  ```
  export PATH=~/bin:$PATH
  ```
  Then you need to create a subnet and deploy it by entering the following commands :
  ```
  avalanche subnet create mySubnet
  ```
  ```
  avalanche subnet deploy mySubnet
  ```
  * After deploying , you get the network configurations which you need to enter in your metamask to connect to the subnet and then import account with tokens by entering the private key mentioned in the network config.
 
 ## Authors
 
 Tanisha Ibrahim
 
 @tanishaassii@gmail.com
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
