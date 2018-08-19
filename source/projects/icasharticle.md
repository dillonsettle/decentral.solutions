---
title: 'Processes for Arbitration on Smart Contracts'
date: 2018-08-19
tags:
- Investors
- Networking
category: "Projects"
author: "Ling Qing Meng"
---


# Processes for Arbitration on Smart Contracts
August 18, 2018

## The Importance of Governance
 

Governance is one of the unsung pillars of the blockchain. Along with the other core pillars such as scalability, privacy, security, and decentralization, some would say governance is the most important problem to solve. Governance pertains to a blockchain ecosystem, in which a near perfect process is in place that allows automation and a self-sufficient economy to survive. Many have come up with variants from the initial Proof of Work to Proof of Stake, Delegated Proof of Stake, Federated Byzantine Fault Tolerance, but we are at a stage where evolution is occurring and there has yet to be a winner.

 

With the many pillars such as governance and decentralization that Blockchain Technology is comprised of, there is a shift from traditional structures to transact in new ways that previously required trust in a centralized entity. Blockchain solutions with the most efficient governance will be the most trusted, thus the most dominant and widely accepted.

 


## Blockchain Governance Issues

Recent issues around EOS have emphasized how challenging the governance issues may become. EOS was built on four pillars: flexibility, usability, governance, and scalability; of which, the governance pillar was tested foremost.


Certain users fell victim to a phishing attack, they, in turn, sent private key information resulting in stolen funds. In response, the EOS Core Arbitration Forum (ECAF) alike to a centralized government body, directed block producers to not process these transactions without supplying logic behind such decisions. EOS attempted to resolve issues by offering to take back power from ECAF, furthering confusion.

![alt text](https://i.imgur.com/pDslrXG.jpg)

Processes for Arbitration on Smart Contracts
The blockchain community criticized the ECAF for overstepping their boundary on what they could enforce in the EOS ecosystem. Initially, they were only responsible for arbitrating on decisions guiding the direction of the EOS blockchain as a whole.

 

Now, having the power vested in ECAF to vote on whether individual transactions may take place effectively goes against the basic decentralized decision-making process which blockchain was meant to address.

 

Following this event, Dan Larimer proposed a revised draft of the EOS Constitution. He stated that arbitrators shall extend only into disputes regarding the intent of the code, as opposed to overseeing users’ assets.


In a world where protocol-level dispute resolution is limited to fixing bugs in the code, how does one protect against fraud and theft of keys? The answer is to opt-in to a banking Ricardian contract which controls the tokens on behalf of their owners.

 

Transfers within the Smart Contract are subject to dispute resolution where the contract-appointed arbitrators have the power to reverse transactions and freeze tokens. Any withdrawals from the banking Smart Contract would be subject to a 3-day delay after which it would not be reversible.


Furthermore, he revised the EOS constitution to incorporate the following changes.


If there is a dispute on the intent of the code, then intent shall be determined by a supermajority vote of elected producers or an arbiter mutually agreed to by the parties to the dispute and enacted by producers. A supermajority may, at their discretion, freeze a contract during an active dispute until such time as the code to fix the contract is available. The parties to the dispute must produce proposed replacement code. The producers may charge a fee and/or place other requirements on the parties to the dispute. A supermajority is defined as 2/3+1.



## The Impact of Arbitration

Arbitration is a process of dispute resolution between two parties, led by an independent third party. The third party can be one or many arbitrators. The goal of arbitration is to obtain a fair resolution of the dispute without unnecessary costs or delays. Generally speaking, the dispute may arise in any situation. One common example is when business A has a written agreement with business B, they dictate the terms into the contract. When the contract needs to be enforced, the arbitration clause comes into play.


As most people understand Smart Contracts being self-executing that the terms of the agreement are represented by lines of software code; in the advent of blockchain technology, we imagine permissionless Smart Contracts shall quickly replace traditional contracts. Discounting a few examples (e.g., contracts used for raising capital) for the vast majority of contracts, this has yet to come true.


Hereinafter, to illustrate a few examples. A Services Agreement is a contract used for employers to set forth terms and conditions for vendors or contractors. It seems from a first glance that blockchain Smart Contracts would be a perfect use case for a decentralized Upwork. Using continuous integration, a bounty is placed on a company’s open source Github. When a developer successfully creates a pull request that passes all of the verification tests, that developer is paid out the bounty automatically by the continuous integration system. All of these events are verifiable on the blockchain—so why hasn’t it become a prevalent use case yet?


At some point, human intervention is required in deciding whether certain terms have been satisfied for a subjective and just stance. For instance, our software service, even if the verification tests passed, the submitted code could still be of poor quality, runs slowly, or simply does the bare minimum in order to pass the tests. Successful service marketplaces such as Airbnb and Uber thrive on the fact that it is very simple to computationally verify whether a driver has driven from point A to point B or, whether a residence had a vacancy for guests. When verification is easy, quality of service can be standardized and the app becomes capable of solving problems on a global scale. When verification is challenging and without human’s discernment, self-executing contracts would still miss a crucial piece that renders them successful in the supposed decentralized world.

 

iCash’s Proof of Trust (PoT) Protocol is an Automated Arbitration Mechanism that is Subjective in Nature and Objective in Function.

 

![alt text](https://i.imgur.com/87Kemxi.png)

There are countless amounts of contracts that require subjective human intervention. A Smart Contract for an insurance policy with a single input source in verifying whether an event (e.g., natural disaster) has occurred is one example which demands human intervention.

 

A financial derivative contract requires an accountable party to give the closest floating point precision price for the underlying asset at an exact moment in time. Both of which are multi-billion dollar industries.



At iCash, our vision is to bridge the gap between subjective and objective Smart Contracts using automated arbitration. iCash’s Proof of Trust (PoT) protocol arbitrates conflicts before events are verified and prior to being recorded on the immutable blockchain. This allows for contestation before settlements deemed irreversible.


Who verifies these inputs? A network of Oracles being delegates that have a proven legitimacy. They are incentivized by the financial gain in verifying the Contract and held accountable via staked iCash tokens and in the KYC registration process. These delegates are ranked and tracked by an algorithm that ensures consistent performance of these delegates. This way, trust is distributed among trusted agents creating a happy medium in the decentralized world with a system of checks and balances without having the power be vested in ECAF


Once parameters are entered into a Smart Contract on the blockchain, 50 basis points (in iCash tokens) are placed into an escrow. If there is no contestation to the initial determination of the Smart Contract, then it enters into the blockchain; and, the funds in escrow are released back to appropriate parties.


If the original Smart Contract determination is contested, the matter is elevated from the Smart Contract, and a full network call is incited. In this case, 25 basis points are paid to delegates. These delegates validate the data in a Boolean voting process (i.e., True/False, 1/0).


If there is no agreement, a second layer of contestation would take place, wherein delegates with the highest trust score (called SuperDelegates) for a given Smart Contract domain will then vote again to reach consensus. If approved by these SuperDelegates, then the prior arbitration is overturned. The decision of the SuperDelegates is what’s ultimately recorded on the immutable ledger.


Based on correctly voting, delegates are given a PoT score on their accuracy. The vision of the iCash team is to enable delegates in providing non-binary or continuous data entries and determinations with respect to probabilities. These determinations become automated, requiring minimal intervention, and offer scalability.



## Conclusion: Blockchain’s Governance Authority and Decentralization Outlook


We have seen that this key value of blockchain can be a double-edged sword. Both EOS and Ethereum have identified that it is of utmost importance for transactions to flow freely without a central authority. As Smart Contracts increase in complexity and prevalence, we will continue to witness this issue being tested. It is an issue of where one draws the line between having a secure user experience v.s. true decentralization.


In June 2016, Ethereum’s governing body, the DAO was compromised and millions of ether were stolen from a Smart Contract. That smart contract was intended to operate a certain way; however, due to human intervention (quite literally) it was exploited and operated in a way that directly goes against the contract’s intended purpose. Like EOS, Ethereum’s core members made the decision to reverse the transactions of the stolen ether, and effectively overstep the system of checks and balances.


During this process, the major decisions on governance shall be created, and many more prior decisions will likely be overturned. These situations will continue to occur as the blockchain community matures and properly defines the standards for governance. Through the process of clearly defining the factors for which each decision is judged on, we utilize prior decisions as precedents to assist in assessing future decisions. This is the start of a standardized process, meaning having a protocol for arbitration, where we make a decentralized arbitration offer consistent, transparent and impartial settlements. With reliable decentralized arbitration, we can then trust Smart Contracts to operate as intended. The Proof of Trust protocol is built so that blockchain governance can evolve to fully exemplify the fundamental values of the blockchain.


In essence, iCash is able to protect users from nefarious data inputs having incorporated a layer of trust and assurance inter-operable across the Smart Contract blockchains. Confidence in the system is hence achieved, paving the way for widespread adoption.

 
