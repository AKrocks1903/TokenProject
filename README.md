NEWMyToken

Overview

This solidity program is to make a simple token, deployed on the Ethereum blockchain. It allows for the creation, distribution, and management of a custom token.

Contract Details

- Name: NEWNAME (specified in the nwTokenName variable)
- Abbreviation: NEWABBRV (specified in the nwTokenAbbrv variable)
- Total Supply: 1000 (specified in the nwTotalValue variable)

Functions

- nwmint(address _address, uint _value): Mints new tokens and assigns them to the specified address. Increases the total token supply.
- nwburn(address _address, uint _value): Burns tokens from the specified address. Decreases the total token supply.

Mappings

- nwbalances: A mapping of addresses to their corresponding token balances.

Authors

- ankitkumarrbt1903@gmail.com
