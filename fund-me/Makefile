-include .env

build:; forge build

deoloy-sepolia:
	forge script script/DeployFudMe.s.sol:DeployFudMe --rpc-url $(SEPOLIA_RPC_URL) --private-key $(PRIVATE-KEY) --broadcast --verify --etherscan-api-key $(ETHERSCAN_API_KEY) -vvvv