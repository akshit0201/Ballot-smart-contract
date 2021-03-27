# Ballot-smart-contract
A simple smart contract for voting.
The given code is written in [Solidity](https://docs.soliditylang.org/en/v0.8.3/) language. It can be run on the [Remix IDE](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null). 

This contract allows a superuser (the chairperson in this case) , to register voters and and let the voters choose their proposal. The system transitions from one state to another after 10 seconds , the four stages of voting are Initialize , Register , Vote and Done.
