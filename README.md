# This a simple lottery smart contract

only have to compile and deploy.

# how it works?

The players will pay an ammount of 0.01 eth to get into the lottery
The deposit will acumulate on the contract
A random number is generated with the keccak256 cryptographic function, this function only accepts one parameter so we concatenate the owner address with the block.timestamp and returns a uint

# how to pick a winner

In order to get a winner we make a variable called index what we to storage the module %
get the rest of the function getRandomNumber with the lenght of the array of players

this function will only be succesful called by the owner(modifier)

# its dployed?

yes on the testnet BSC = https://testnet.bscscan.com/address/0x1aa7aea9ba53eea4d233b61f7bc333167fdbb37c
