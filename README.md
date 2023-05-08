need to add:
.env - keys
.secret - seed 

install OpenZepplin contracts:
forge install openzeppelin/openzeppelin-contracts

to build:
forge build

Run deploy Script:
forge script script/Deploy.sol:SpacebearScript --broadcast --verify --rpc-url ${GOERLI_RPC_URL}
