## Oxygenn ERC-20 Token Smart Contract

# Contract Overview

**Contract Name:** Oxygenn
**Inheritance:** Inherits from ERC20 and Ownable (both from OpenZeppelin).

# Constructor

1.Accepts an initialOwner address during contract deployment.
2.Calls the constructor of Ownable with the provided initialOwner.
3.Calls the constructor of **ERC20** with the token name **“Oxygenn”** and symbol **“Oxy”.**

# Functions

**burnToken(uint256 amount):** Allows the sender to burn their own tokens.
**mintToken(address receiver, uint256 amount):** Only accessible by the contract owner. Mints new tokens and assigns them to the specified receiver.
**transferTokens(address receiveraddy, uint256 amount):** Allows the sender to transfer tokens to another address.

# Video Reference
[Detail Explain of the code](<https://www.loom.com/share/7916fe545798480aa21b8a4b19f059c4>)


