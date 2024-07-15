#ERC20-MynUiqueToken
MyUniqueToken (MUT) is an ERC20-compliant token for decentralized applications, ensuring compatibility with existing Ethereum systems and exchanges.

Features

ERC20 Standard Compliance: Compatible with most wallets and exchanges.
Ownership Control: The deployer is the owner with exclusive minting rights.
Minting: Only the owner can mint new tokens.
Burning: Any holder can burn their tokens.
Transfer: Seamless token transfers between users.
Contract Details

Variables: owner (address of the contract owner).
Functions:
constructor(uint256 initialSupply): Assigns initial supply to the owner.
mint(address receiver, uint256 amount): Owner mints tokens to a specified address.
burn(uint256 amount): Holders burn their tokens.
transfer(address recipient, uint256 amount): Standard ERC20 transfer function.
