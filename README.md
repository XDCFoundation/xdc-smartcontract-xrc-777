# xdc-smartcontract-xrc-777
xdc-smartcontract-xrc-777


# XRC 777

This set of interfaces and contracts are all related to the [ERC777 token standard](https://eips.ethereum.org/EIPS/eip-777).

The token behavior itself is implemented in the core contracts: {IERC777}, {ERC777}.

Additionally there are interfaces used to develop contracts that react to token movements: {IERC777Sender}, {IERC777Recipient}.


## Usage

#### This XRC777 supports the following methods-
- name
- symbol
- decimals
- granularity
- totalSupply
- balanceOf
- send
- transfer
- burn
- isOperatorFor
- authorizeOperator
- revokeOperator
- defaultOperators  
- operatorSend
- operatorBurn
- allowance
- approve
- transferFrom

### Requirements:
- Solidity 0.5.5
