1. We are going to have a contract controlled by a DAO
2. Every Transaction that the DAO sends has to be voted on
3. We will use ERC20 tokens to vote ( there can be other methods to vote on)

We need to make the contract Ownable by the DAO

Voting is done using ERC20 Tokens

We are going to deploy a contract called TimeLock (Every single DAO should have this contract) which means that the proposal will be controlled by TimeLock and not the Governor. TimeLock will own the Governor
Every time the Governor has voted on something, the governor says okay you will have to wait certain amount of time

hello