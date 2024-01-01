# Kellogs Gaming(DeFi)

 The token is named "kellogs" with the symbol "KLG." This game contract is deployed to local subnet using WSL.

## Description

**Total Supply:** The total supply of the token is tracked.
- **Balance Tracking:** The contract keeps track of the balance for each address.
- **Allowance:** Allows users to approve and transfer tokens on behalf of another address.
- **Minting:** New tokens can be minted by calling the `mint` function.
- **Burning:** Tokens can be burned using the `burn` function.
- **Blessings:** The contract has a feature to provide blessings based on a random number.

 ## Getting Started
 
 ### Executing the code
 
Make sure you have avalanche CLI installed else refer to this docs:
 
[https://docs.avax.network/tooling/cli-guides/install-avalanche-cli]

We create avalanche subnet by typing:

```cmd
avalanche subnet create <subnetName>
```

and choose:

- **Subnet-EVM**

- **ChainId:** 2567

- **Token symbol:** PPGM

- **✔ Use latest version**
- **✔ Low disk use    / Low Throughput    1.5 mil gas/s (C-Chain's setting)**
- **✔ Airdrop 1 million tokens to the default address (do not use in production)**
- **✔ No**

Deploy the subnet by running:

```cmd
avalanche subnet deploy <subnetName>
```

- Connect it to Metamask

- Connect Metamask account to Remix and deploy the contract.
 
 ## Authors
 
 Praneel Patel GM
 
 [@praneelpatel88@gmail.com]
 
 ## License
 
 This project is licensed under the MIT License - see the LICENSE.md file for details
 
 
