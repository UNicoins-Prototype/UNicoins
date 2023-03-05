# UNicoins
This is the repository for the UNicoins technical prototype. 

## What are UNicoins?
UNicoins are digital tokens  representing UN personnels' time spent on cross-UN collaboration. The tokens are a nonmonetary
unit of value that can be exchanged among project managers and/or collaborators in recognition of collaboration hours contributed to cross-UN work.
UNicoins are an ERC-20 digital token built on Ethereum. 

## How it works 
Alice, a UN personnel, posts a task in the cross-UN marketplace which she needs some help on. 
Bob, a collaborator in the cross-UN marketplace, takes up the task. Bob receives UNicoins for time spent on the task. Each UNicoin represents an hour of work completed. Bob can then donate his UNicoins to other cross-collaboration initiatives where he requires help from other UN personnel. 

![diagram explaining how UNicoins flow through the system](https://github.com/UNicoins-Prototype/UNicoins/blob/main/Screen%20Shot%202021-09-08%20at%204.10.23%20PM.png)

## Technologies used in initial prototyp
- Solidity is used to write the initial smart contract for the ERC-20 token. Tokens can be accessed on the Rinkeby test network via a Metamask (or other) wallet. 
- Aragon is the platform on which the UNicoins Decentralized Autonomous Organization (DAO) is created. It encompasses all holders of the UNicoins token for community governance purposes. 
- Gnosis safe is a multi-signature wallet from which votes can be cast to transfer tokens. Administrators can use Gnosis safe to approve transactions of UNicoins to individual contributors. Gnosis forms the basis of prototype distribution of UNicoins

## Smart Contract upgrade for ETH Denver 
- Solidity is used to write the smart contract for the UNicoins ERC-20 token with additional functionality based on the UNicoins White Paper. 
- Embedded functions include the creation of users Project Manager (individual or DAOs) and Collaborators (volunteers). 
- Functions of Project Manager is to create projects, create tasks within a project, assign tasks to collaborators, authorize transfer of UNicoins tokens corresponding to the hours contributed to a task, and create badges. 
- Collaborators are able to be assigned tasks, complete tasks, and receive UNicoins corresponding to their hourly contribution to the task as well as badges. 

You can **view the whitepaper on UNicoins [here](https://drive.google.com/file/d/1T56L0qzoipCpZFGe-abW5BDmDRWV2p9J/view?usp=sharing)**

### Calling all potential collaborators
The UNicoins team is looking for individuals and institutions willing to help with the development of this project. If you have any ideas as to how we could potentially improve this project, please reach out!

You can [view the UNicoins proposed app structure here](https://docs.google.com/spreadsheets/d/1cLsQp2KSmuRWnGgsj4bvzx4Zzxli4-ds/edit?usp=sharing&ouid=103741152089559543137&rtpof=true&sd=true). We are calling for contributors to any of these features. We would really appreciate your help!


Follow us on [Twitter](https://twitter.com/unicoins_un). 


