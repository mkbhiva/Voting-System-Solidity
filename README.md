# Decentralized Voting System

We have developed a Smart Contract in Solidity for voting system.  This smart contract having some of the few functions which are given below:

## Overview
Election commission can register the candidates in the Smart Contract before election.
Where a voter has to first get itself whitelisted on the smart contrct from Election commission.
EC can only to start and strop the voting event. 
EC should not be able to take participate in the voting. 

### Usage

**registerCandidates**
The registerCandidates() function perform by EC only to register a Candidate with his name, age and address.  With this function, EC can not register ourself as a candidate and also one check with existing candidate or not. 

**whiteListAddress**
The whiteListAddress() function perform by EC only to allow voter to take participate in voting. Only those voters can take participate who has whitelisted by EC only.  We have also check with this Smart Contract that EC can not be a part of Voters.

**startVoting & stopVoting**
The startVoting() function perform by EC only to start the voting and stropVoting() function to stop the voting.  

**getWinner**
The getWinner() function perform by EC only to get the winner.   

## License

This Contract is released under the [MIT License](LICENSE).

