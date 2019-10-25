# Reentrance-attack-on ethereum smart contracts.

Assuming that one has already know the deployment of the contracts on the ethereum platform.
For reference go through the following medium article
https://medium.com/coinmonks/creating-deploying-a-smart-contract-using-truffle-framework-ganache-cli-part-2-f2dcf400fbde

# Reentrancy attack
The fallback mechanism may allow an attacker to re-enter the caller function. This may result in unexpected behaviors, and possibly also in loops of invocations which eventually consume all the gas.

Basic notion and the explaination of attack can be found in the article https://medium.com/@gus_tavo_guim/reentrancy-attack-on-smart-contracts-how-to-identify-the-exploitable-and-an-example-of-an-attack-4470a2d8dfe4 .
.
# Frameworks and their versions used:
  Solidity : v0.5.8 
  Ganache-cli : v6.7.0
  Truffle : v5.0.41

# Note 
Commands in the "Console_cmnd" shows the changes the attack and the changes of the balances in the accounts.
