# Whitepaper-2.0
Updated Whitepaper of the Datagen cloud computing infrastructure 

echo "# Whitepaper-2.0" >> README.md







## Datagen Project








**Whitepaper 2.0**
























**Premise:** *The Original Datagen Whitepaper{1} offered us a first glimpse into the project, declaredly without entering too much in technical detail. Knowledge is a journey and the“DATAGEN WHITEPAPER 2.0” is bringing the Datagen journey to the next stage. 
Blockchains store immutable data, but the “shape” of the same Blockchains evolve while they are bug-fixed, improved or while they migrate to a totally new consensus protocol.* 

The Datagen Whitepaper 2.0 expands, deletes, and amends ideas previously expressed in the Original Whitepaper: a greater understanding of the best technology solutions, the evolution of the market and of the competitive landscape and simply all the knowledge accumulated in the journey from the writing of the Original Whitepaper generated changes in the development path of the Datagen infrastructure that must also be reflected in the Whitepaper.

*The Datagen Whitepaper 2.0 is not the final destination for Datagen, but just another stage of its evolution, since the destiny of all alive beings (be they biologically or intellectually alive) is to evolve or die.
The Theseus’ Paradox{2} is a thought experiment that raises the question of whether an object that has had all its components replaced remains fundamentally the same object. The original paradox wondered whether by replacing, one by one, all the components of a ship the resulting ship still has the same identity of the original one. 
Similarly, many ideas will replace those expressed in the Original Datagen Whitepaper: solutions for decentralized cloud computing are taking the main stage and their technical overview is greatly expanded. Conversely, other ideas explored in the Original Datagen Whitepaper like the Privacy Friendly Search Engine, Minidata, the exchange Portal, are fading either to the margin of the stage or to the backstage, where wonderful but useless contraptions are discarded (maybe to be retrieved later, maybe to stay there, in the dust, forever). 
This is not a betrayal of the vision expressed in the Original Datagen Whitepaper, but its fulfillment, exactly like in the Theseus Ship: the wooden planks devoured by the salty water, or the ropes consumed by their incessant use must be replaced for the ship to fulfill its purpose of being a functional vessel. In the same way, to fulfill the purpose of the Datagen infrastructure, which is to fuel the Data-needs of the Web3 world, the Datagen Whitepaper needs a metanoia towards a more concise, technically precise, and less byzantine document revolving around an infrastructure for GPU/CPU computation, to mirror the direction that the Development of the Datagen Project is undertaking: the “Datagen Whitepaper” needs to evolve into the “Datagen Whitepaper 2.0”*


**Note: The Datagen Whitepaper is analyzing the need for and characteristics of an ideal decentralized network for GPU/CPU Cloud Computing - Not for Cloud Storage{3}**
Cloud Computing and Cloud Storage networks share many core features and many assumptions made for decentralized GPU/CPU Cloud Computing could be true even for decentralized Cloud Storage. However, many different factors, which are not the subject of this whitepaper (such as different hardware and software requirements), entail that, to be performed in economically efficient ways, both GPU/CPU Cloud Computing and Cloud Storage require separate architectures. That’s why, in continuity with other existing solutions, we only analyze the need and the characteristics of a GPU/CPU Cloud Computing network.
Cloud Storage needs could be addressed separately, notably with the use of APIs or other solutions to connect to exisiting cloud storage stacks or protocols (e.g. Filecoin{4} or IPFS{5}).




**Why the World needs a Decentralized Cloud Computing Infrastructure**

Web3 flourished to correct the shortcomings of centralized Web2, exactly like Crypto flourished to correct the shortcomings of centralized money and DeFi the mistakes of centralized finance {6,7}.
When Web3, Crypto or DeFi projects resort to use centralized tools for their critically important inner works they are undermining not only the ideal decentralization principles that sparked the Web3 revolution, but also their products’ security, resiliency, transparency{8}. 
Web3 applications and Proof of Stake (or "PoS") validators are still heavily reliant on centralized computational stacks. As cloud computing is the deepest and one of the most critical layers for any Web3 project, the overreliance on them is posing a strategical risk for any Web3 project (e.g. PoS blockchains, a decentralized metaverse or a privacy friendly search engine) making them more vulnerable to censorship, downtime and efficiency issues.

**The Datagen network, is a blockchain-based GPU/CPU Cloud Computing infrastructure for on-chain computation. It will include a Layer1 and a Layer2 substrate-based blockchains, with an asynchronous randomized consensus protocol, that will allow low-latency and efficient computation, with a higher degree of decentralization, even at the hardware level.**
In this whitepaper we will explain the general design principles of the Datagen architecture and how the above stated characteristics can be achieved.
But, before, we need to explain what is already there and what the Datagen infrastructure is not. Why and how, choosing different paths, the Datagen infrastructure can be better equipped to reach the goals of speed, efficiency, and improved uptime with a rigorous decentralization process.



**Why the Decentralized Cloud Computing Infrastructure that the World needs can’t be off-chain**

Blockchain technology was not originally created to perform Cloud Computing efficiently{9}. 
Blockchain was created to reliably store immutable data, making them impossible to falsify and not reliant on opaque centralized authorities. 
The focus on these stated goals vs efficiency is self-evident when looking at the energy consumption of first generation Proof of Work (or "PoW") blockchain networks. Afterwards, the problems generated from the modeling of the original PoW consensus protocols (namely staggering energy consumptions{10} and very high transaction costs) have been mitigated by the second wave of consensus protocols: PoS consensuses{11}.
The incremental efficiency of PoS technology, compared to PoW, offered interesting solutions to decentralized Cloud Computing networks in terms of efficiency, but no solution to the problem of speed: even in PoS, data needs to propagate to different nodes and Validators{12,13,14} and this takes a very long time, compared to the Cloud Computing industry standard latency-time.
That’s why some decentralized Cloud Computing projects{15,16} took the short-cut of moving the computation off-chain. 
The technical approach of moving the computation off-chain is becoming increasingly popular in the industry, since it improves the latency time performances without the need for very complex architectures. 
The main problem of this approach is that the blockchain technology is removed altogether from the equation when it comes to the computation itself and is just re-introduced in a cosmetically pleasing way for secondary features of those off-chain networks, such as smart contracts to match supply and demand or similar tools. 
But: 

a)	The problem of trust is not solved, since the computational process itself is left to the goodwill of the supplier, like in centralized systems; 
b)	Such networks are solving the latency time issues removing blockchain-nodes from their data infrastructure and incentivizing the Cloud Computing suppliers to be hosted in scaled, “reliable” and “cost-effective” centralized server farms. 

Relying on centralized providers makes the users of the network vulnerable to the same censorship, downtime, and efficiency problems that they are trying to move away from.
We don’t believe that off-chain solutions are without merits or without use-cases: smart contracts can add security and transparency layers to the Cloud Computing processed by centralized providers, and this is certainly an improvement, but we should not use centralized providers as foundational layers for core /native Web3 applications or, worse, ecosystems, reducing Web3 to a loosely decentralized layer built on the top of the likes of AWS.

Off-chain solutions should be used only when viable on-chain solutions are not available, since on-chain is more resilient, more transparent, more inclusive, but also less prone to censorship, to unsecure computation and to cybersecurity hazards.




**Why the Decentralized Cloud Computing Infrastructure that the World needs can’t be built using a general purpose Layer2 or a general purpose PoS consensus protocol**

Being Layer2 has benefits: 

1.	Layer2s are efficient{17};
2.	Creating a Layer2 is usually simpler{18} than working around a Layer1, development-wise.
 
Why not using a Layer2 only? 

Layer2 usually needs at least to respect the blocktime of the underlying Layer(s). 
This means that any Layer2 built on Ethereum will have a blocktime ≈12 seconds or greater and any (classically defined) Layer2 built on Polkadot or Cosmos will have a blocktime ≈6 seconds or greater. The apparent solution would seem to be a sidechain{19,20}, since they can have their own blocktime, but sidechains don’t inherit the security of their “parent” blockchains and so, for the moment, we’ll deem sidechains as imperfect, although perfectible, solutions{21,22} (we’ll come to that later, speaking about Datagen integration with the Polkadot ecosystem).

Implementing a Cloud Computing infrastructure on a general-purpose PoS protocol, with standard data propagation to different nodes raises different problems: 

a)	Economy of scale moved from hardware availability to the availability of coins, tokens or assets to be staked{23}; 
b)	Standard data propagation models, where data need to reach many nodes before reaching back the user, are levelling to 0 the latency-time competitive advantage of being geographically close to the user and so are decreasing the incentives to be bare metal or geographically decentralized{24};
c)	PoS is already moving the initial capital costs of validating firms from purchasing machinery to purchase tokens to be staked. This shift allows validating firms to improve furthermore their economic efficiency by converting the operative costs required to manage independent GPU/CPU machines to the much more easily manageable capital costs required by simply renting computational power at a more predictable capital cost inside centralized server farms. 
d)	PoS protocols are usually built to validate transactions of digital assets and execution of smart contracts (etc.); they are not customized for Cloud Computing.
e)	The relative slowness of the blocktime (≈15-20s for Golem{25,26} and ≈6s for Akash{27}  and Cudos{28}) limits the use-cases to very low-latency time segments (E.G. image rendering).



Standard PoS solutions are often just adding the unnecessary complications of moving processes on-chain, adding at least other three complex layers without solving the centralization pain points.  
E.G. the overreliance of Akash on Solana Validators to source Cloud Computing, then sourced by Solana’s Validators mostly from Google Cloud Platform (or "GCP") or AWS {28,29,30}. 



**Why the Decentralized Cloud Computing Infrastructure that World needs could just be a Layer1, but it’s a Risky Bet**

The simpler solution to all the problems assessed until now could simply seem to be a properly designed standalone Layer1: when designing a Layer1 you can customize many parameters, including blocktime, runtime, consensus protocol and you can even design proper incentives so that some Validators can choose to be independent from centralized server farms without being strangled. 


So, why not just using a Layer1?



Let’s see a concrete example.
The data infrastructure Oort{31} (formerly known as Compute Coin) is an example of good design for a Layer1 based Cloud Computing infrastructure (at least on -white-paper, since as of late 2022, it is still under construction): they can integrate PEKKA, a native Layer that is aggregating cloud computing from different sources, with MCP, a native Layer1 with a highly customized consensus protocol (Proof of Honesty -PoH-) using EntrapNet algorithms to entrust nodes with cross-check phishing tasks. Without analyzing further the consensus protocol of Oort, it is clear that, by virtue of being a Layer1, Oort can potentially have much greater customization advantages compared to Layer2 networks like Akash or Cudos. 
So, where is the caveat?
The problem is clearly stated in the Compute Coin’s whitepaper{32} “Assumption 1. The blockchain network used in the EntrapNet is reliable.”
Reliability assumptions can be dangerous in a 0 Trust perspective.

A Layer 1 must consider many threats which are much more mitigated for a Layer2:

a.	Attacks 51 or similar attacks are easier to be performed against smaller networks; 
b.	Building a blockchain from scratch implies much more development, much more things can go wrong; 
c.	Being insular, the developer community is much smaller and so it is less probable to find bugs before malicious actors do. Bitcoin itself had many critical bugs and, without the support of its developer community, many things could have gone wrong{33}; 
d.	Lack of support from other projects, developers, investors, users already involved in existing ecosystems;
e.	Total freedom can be too much freedom: once you have total freedom on how you want to design a stack and if the team that is working on this is relatively small you have less feedback and less scrutiny from the developer community as so is easier both to underestimate problems or to add malicious code. 
f.	No shared security features with any underlining protocol; 
g.	No shared validating resources with any underlining protocol.


While the problems above seems really vexing for Layer1 developed from scratch, a much less customized Layer 1, for instance copy-catting the source code of an existing EVM compatible blockchain, would imply a smaller chance to incur in those vexing risks, but won’t allow for the customization features for which you want to use a Layer1 in the first place.


**A Layer1 solution seems theoretically viable, but in practice difficult and risky to be implemented.**

![image](https://user-images.githubusercontent.com/88165605/207418261-06548bef-40b6-408e-9515-392239e6e8b2.png)




 




**Why the Decentralized Cloud-Computing Infrastructure that the World needs must be efficient**

The Cloud Computing industry (including Cloud Storage and other segments out of scope in the present Whitepaper), as of 2022, is emitting 2.5-3.7% of Global Carbon emissions{34} slightly more than the aviation industry. 
For this reason alone, it is of the outmost importance for any network setting itself to be part of the solution and not part of the problem, to consider efficiency in its design{35}. When we couple environmental responsibility with the higher cost that the user is paying when unnecessary computational workloads are performed by a network, this makes the solution of this problem of the most paramount importance.
Any decentralized blockchain-based network will lose some computational efficiency (compared to centralized ones) since at least some data will be validated multiple times by Validators and stored multiple times by nodes. 
If this loss of efficiency is light, its environmental cost can be more than offset. 

How?

a.	A more geographically dispersed network of Validators can put less strain on local energy grids and local water supplies; 
b.	Given the smaller energy requirements, can run more easily on locally produced renewable energy;
c.	It is more feasible to rely on micro grids and local energy storage;
d.	Avoiding that environmentally expensive hardware is staying idle, due to a more flexible and dynamic allocation of it.




The Datagen network must try to achieve a slight loss off efficiency, keeping to the minimum (for security and decentralization efficiencies) the average number of double-checks on specific computational processes.
At the same time, Datagen must keep to the minimum the amount of data which is hashed and saved on-chain, to avoid the proliferation of unvaluable data stored in multiple nodes.



To explain it, let’s give a **closer look at the Datagen architecture.**


![image](https://user-images.githubusercontent.com/88165605/207418738-1a8e0fc1-8d70-43e6-a187-9af6c81d5e07.png)





 






The **Datagen Infrastructure** is designed with **two separate blockchains with different functions:** 

•	the **Fast Blockchain**'s (in blue), where Validators are also the providers of Cloud Computing in the network

•	the **Heavy Blockchain** (in pale red), is a Proof-of-Stake blockchain that manages in the most computationally-efficient way possible some functions indispensable for a secure blockchain 


The User is requesting Cloud Computing to the network. 
Users can be either “solo” requestors, that are at the same time requestors and final users of the received data (e.g. Validators of third party PoS blockchains like Polkadot, Binance, Cardano or Cosmos{36}), or a requestor pooling data to and from final Users in plural locations (e.g. the requestor is a gaming application managing workloads for end Users/ gamers in different areas of the world), therefore “pooled” users.


To understand better the different functions of the two blockchains, let’s follow the path of the to-be-computed (and later computed) data: 
 
a.	Both “solo” and “pooled” final Users usually interact with the Datagen network through APIs (APIs and applications pooling data from and to users are not shown in the diagram for a better abstraction);

b.	When the User connects to the network for the first time, a package of data is sent , through an off-chain router/worker, to all the Validators of the Fast Chain;

c.	All the Validators of the Fast Chain process this first package of data;

d.	The package of data at the same time: 

i.	is hashed in the Fast Blockchain; 
ii.	goes back to the off-chain router/worker and then to the User; 
iii.	is hashed and potentially sent to and stored in the Heavy Blockchain;

e.	Using timestamps, it’s measured whose validator was faster in processing the first package of data and in sending it back to the User;

f.	The procedure is called Echo; The results of the Echo are hashed and saved on-chain -could be either the Heavy or the Fast Chain-;

g.	Using the results of the Echo procedure, Users and Fast Chain’s validators are paired on individual basis. 
From the moment of the pairing, the computational requests of an individual User will be processed only by one, individual validator of the Fast Chain. 
This pairing happens:

-	latency-time wise, for the standard user 
-	or using only randomness for those users for which the strategic value of sourcing cloud computing in a more randomized and cyber-secure way is more valuable than optimal latency time-pairing (e.g. validators of PoS blockchains using the service to source secure cloud computing);

h.	The Echo, which is computationally expensive, will be repeated periodically (every x time, with order of magnitude of weeks or months) or if the Paired validator goes down or anytime at request and expense of the User;

i.	The User will start sending Raw Data to his Paired Fast Chain validator (off-chain, asynchronously from what is happening on-chain);

j.	The Paired validator of the Fast Chain processes and hashes the data;

k.	At the same time: 

1.	the Paired validator will send the processed data back to the User (off-chain, asynchronously from what is happening on-chain), hash included. 
2.	the Paired validator sends the hashed data to the Fast Chain, where is shared with multiple nodes of the Fast Chain and stored on-chain;
3.	the Paired validator sends the hashed data to the Heavy Chain, where is stored on-chain;

l.	The final User has received the processed data and he sends to the Heavy Chain both the Raw data that he had previously sent to the Paired validator and the hash that he had received from him (this could be done either systematically or random, being a random solution preferable, since is a less computationally expensive one);


m.	The Heavy Chain, using a random selector, randomly selects some specific computational problems to be cross-checked and randomly select three validators of the Fast Chain to perform the double-check. The three-cross checkers must be different from the Paired validator whose computational work is being double-checked; The Heavy Chain and the Fast Chain are “speaking” using an RPC;


n.	The three cross-checkers send the hash of the double-checked data back to the Heavy-Chain;


n.	The Heavy chain confronts the hash provided by User, Paired Validator and the three cross-checkers:

n1.	If the hash provided by User, Paired validator and all the three cross checkers are matching, the Paired Validator will pass the test: no consequences;
n2.	If the hash provided by User and Paired validator are matching, while the hash provided by the three cross-checkers is not matching: the Paired validator must pay a price (it’s implied the Paired validator was sending false results); 
n3.	If the hash provided by User and Paired validator are matching and, at the same time, the hash is matching with the one provided by 2/3 of the cross-checkers: no consequence for the Paired validator and for the matching cross-checkers, but the cross-checker providing a false result will pay a price; 
n3.	If the hash provided by User and Paired validator are matching and, at the same time, the hash is matching with the one provided by 1/3 cross checkers: there is substantial parity (Paired+1 Cross Checker vs 2 Cross Checkers). The cross-check can be repeated, entrusting it to a fifth validator as decisive cross-checker to win the majority and the losers will pay (this is unlikely, since it would imply a plurality of errors or collusions); 
v.	If the hash provided by the User is not matching with the one elaborated by the three cross-checkers: the double-check is invalidated, regardless of the eventual matching or lack of matching between the hash provided by Paired validator and the cross-checkers (implying that also the raw data that the User provided to the Heavy Chain, later feed to the three cross-checkers, was unreliable).


Consequences of this process on the computational efficiency, latency time and hardware distribution of the Datagen network:

1.	Pairing on a 1:1 basis Users and validators can avoid much unnecessary double computation, and the overall efficiency of the network can be increased; 

2.	Randomizing double checks, is possible to check just a small percentage of the computational problems. Checking just an increasingly smaller percentage of the computational problems implies a proportionally decreased loss of efficiency (compared to checking all the validators’ activity). For example, double-checking 1% of the computational processes (with 3 cross-checkers) implies an inherent loss of efficiency of just ≈3%, compared to a scenario in which no validator is cross-checked (as it would happen in centralized scenarios); 

3.	Computing and sending data back to Users asynchronously from what is happening on-chain implies that such data don’t need to propagate to multiple nodes before reaching back the User and implies both that: 

a.	Computational results can potentially reach back the user faster than the blocktime; 
b.	Individual validators have a different latency time in regard to specific Users;

4.	Being the latency time response to specific users different from individual validators to individual validator, validators will have different competitive advantages regarding the probability of winning the pairing with specific Users. The main latency-time factors will be hardware and software processing speed and the internet connectivity time required for the data to go back and forth from user to validator + the opposite way. This implies that there will be an incentive for validators to have the lowest latency time possible, to win the greatest possible number of Pairings (since being Paired with more paying users = more economic reward). 

a.	The incentive to have faster hardware and software will ingenerate a race to have faster performing machines (aided by performant software), that will decrease the overall average latency time of the network (faster validators have more users, slower less, too slow none); 
b.	Since the other component of latency-time is the time required for the raw and processed data to go back and forth, validators will also compete to be closer to the biggest number possible of users, meaning that there will be a bigger incentive to have at least a certain number of validating activities outside of major server farms, to win clusters of users far from the big global server farms, for example in Africa or Latin America;



This design makes the Datagen network working on principles close to edge computing, although in a decentralized blockchain-based framework. 

•	Saving only the hashed data is much lighter than saving the whole computational process and allows nodes to save store capability;

•	Offloading many functions (that otherwise would have been performed by the Fast Chain) to the Heavy Chain can make the Fast Chain much more performing.







**What framework is the Datagen network built with and why?** 

Datagen Infrastructure is built using Substrate{37}.
Substrate allows:

1.	modular development; 
2.	great flexibility; 
3.	many modular development elements, called “pallets”{38}) already developed by other teams, which allow us to save on development time; 
4.	with the right development efforts all sort of useful customized pallets can be created; 
5.	a vibrant community of developers and projects; 
6.	the creation of blockchains that can upgraded in a forkless way just using consensus features. This can be greatly beneficial long term for a smooth and easy process of improvement of the Datagen infrastructure; 
7.	correlation between Substrate and the Polkadot ecosystem, with the opportunity to work both with Polkadot’s Rely Chain and to find synergies with other projects in the ecosystem. 


There are other elements of the project, like the token and tokenomic smart contracts built using Solidity EVM-compatible BSC and other languages and frameworks are used for the frontend elements.



**Why we underlined interrelation between Substrate and the Polkadot ecosystem**

While both the Fast Chain and the Heavy Chain could theoretically and effectively be built as two separate standalone substrate-based L1 blockchains, building the Heavy Blockchain as a Polkadot’s (or Kusama’s) Parachain{39} can be a great opportunity, since Polkadot/(Kusama)’s Parachains have the same scalability of a sidechain, but inherit the security features of their “parent” blockchain (the Rely Chain of Polkadot/Kusama) as a Layer2 would have. 
Having the best characteristics of both sidechains and classic Layer2, a Parachain can help the Datagen network to have the same security level of a Layer2 and the same scalability of a sidechain. 
These scalability+security features are achieved thanks to a common characteristic that all Parachains have: Collators.
Parachains can have customized consensus-protocols, PoW, PoS or whatever, and can select the way in which their validators are validating transactions. 
Collators have the vital role to collect transactions from users (deemed valid according to consensus protocol of the Parachain itself), aggregate them in one block and send them unsigned to one or more Validator(s) responsible for proposing the state of a block of the Parachain, to be afterwards signed also in the Rely Chain.
Given their critical role, Collators are deemed reliable after a careful scrutiny, with a 2/3 verification from a set of Validators that are issuing statements about the validity of candidate Collators. 
Another useful feature of Parachains is the possibility to develop them with a customized consensus protocol.
Without going too deep into the description of the Consensus of Polkadot /Kusama, it is enough to say that it can be easily adapted without too many modifications, for the functionalities of the Heavy Chain, where is ideal to have few, but reliable, block authors capable of managing all the randomized processes explained before.
A robust, reliable, resilient Heavy Chain in the form of a Parachain can manage in an authoritative way also the consensus protocol of the Fast Chain and the Fast chain validators can receive authoritative instructions from the Heavy Chain (whom they are going to pair with, who is going to perform the random double checks, which Fast chain validator is admitted in the chain and who is expelled or must pay a price for not passing a cross-check, etc…) without the need to reduce the security level of the Fast Chain itself.

The use of a Polkadot (/Kusama) Parachain could be the right combination for the implementation of the Decentralized Cloud Computing Infrastructure the World needs.



**How the Datagen tokeneconomic and the DataGen (#DG) utility token can aid the Datagen decentralized infrastructure**

The mere fact that the Datagen infrastructure is providing cloud computing{40} to Web3 applications and to PoS blockchains’ validators is not enough to justify the presence of a native utility token, considering that payments could be performed otherwise using stablecoins, ETH or DOT.
 
We need our native token to increase the economic efficiency, caused by the computational inefficiency of the decentralized processes and security features of the infrastructure, and to make the service as affordable as possible for the user. 
We must consider different factors: some driving prices up and some driving prices down.

For example, in a decentralized network, the hardware could be less optimized (cooling pumps, etc…) and this factor alone could make computation less efficient, energy-wise, and energy has an economic price. Another factor driving up prices is that cross-checks, hashing and other functional processes (that are not happening in centralized networks), are consuming computational power that is not used to solve computational processes for which the users are paying. 

A proper design can help to start a race between validators to be the fastest but is also possible to design some mechanisms to start a race between validators to be the most price-competitive, driving down prices.

For example, smart contract-based price bidding mechanisms can set a formal market price range. Users offering too lower prices won’t have cloud computing validated and validators requiring too expensive prices won’t sell cloud computing to users.
This triggers the right incentives for validators to invest in efficiency improvements, as inefficient validators, asking prices out of market range, cannot survive unless they invest capital to make themselves more efficient and affordable.
This phenomenon is at the same time cause and effect of a network in which the hardware stack is more decentralized: if all or most of the validators are hosted inside AWS, they will all have a mostly flat capital cost for their operations, since the price charged by AWS and AWS competitors is usually in a certain range. 
As long as validators are satisfied with this status quo, market price = AWS price + validator’s margin. 
For most validators could be enough to cash the profit surplus obtained after subtracting the price AWS is charging them, until a single validator realizes that AWS itself is selling the service at a profit and that AWS profit is eating the validator’s own margin. 
Even more, that single validator realizes that AWS server farm location (for example in the Netherland) is not optimal to win pairings with customers situated in a remote location like Eastern Africa and then realizes that the price of electricity in Tanzania is roughly 1/3 of the electricity price that AWS is paying in the Netherlands{41}.

A rational validator, having realized that: 
1.	there are paying customers in Eastern Africa; 
2.	he is better positioned to win the pairing with them by relocating his computing hardware closer to East Africa;
3.	he can even further increase his competitive edge avoiding paying the AWS’ margins by emancipating himself from it; 
4.	once free form AWS he is able either to bid for lower prices (winning more customers and avoiding that his hardware ever stays idle for lack of demand) or he can increase his margins with the same number of customers; 
5.	he can increase his margins even more by moving operations in Tanzania, where energy bills are lower.

After those realizations, our single validator could decide to act accordingly.
Some other validators may not do it, since moving operations to Tanzania requires solving additional logistic problems; but someone else will do it, and that pioneer will start a race to move operations to physically decentralized locations. 
When a sufficient share of the network’s validators will move their operations to decentralized locations, the validators that has decentralized their operations will force other competing validators either to do the same or to be constrained to the crowded markets that are both: 

a.	in a physical location close to the AWS server farm, so that being hosted by AWS can still be a latency-time advantage; 
b.	segments in which Users are willing to pay a premium for a better latency-time response. 

Some users could decide to pay more, entrusting their computational power to more expensive validators, but this won’t affect their capability to turn away at-will the expensive validator, that must compensate higher prices with other premiums like improved latency time or improved uptime, in order to retain Users, since the User could opt for cheaper ones.

This process doesn’t have the only merit of making the Datagen network more emancipated from centralized providers, but also offers the opportunity to drive down the average prices that the users are paying. 



**Where the token fits in?** 

Competition by itself can help to drive down prices, but this is effective only once the network has grown enough to have a real global competition between hundreds or even thousands of validators and when there is a great number of users, so that there is enough distributed global demand, enough for a validator to set up an independent validating facility, so that he can address the demand of specific regions. 
Only a grown network, with a reasonably forecastable continued long-term existence and operation, can justify the risk of building from scratch a validating activity somewhere remote, vs just renting from AWS{42}. 
At the same time, in a network with a still small number of validators, a few of them can easily collude in a cartel to keep prices high; and, since the first Users to try the network will be a small number of applications with a very important strategic reason to do so (let’s imagine validators of a PoS blockchains with incentives from a foundation), they will be willing to pay a very high premium. The high premium will keep validators profitable even when their operating expenses are relatively high, giving no special reason for the validators to innovate and invest so that they can become more competitive price-wise.
High premiums could attract more validators, but, without organic growth of the demand base, eventual bursts in the supply will make price drop fast enough for validators to abandon the network, leading to the price fast growing again and to cyclic alternance of long high-price phases and short low-price phases, keeping in the network only the above-mentioned users with very strong strategic reasons to do so, accepting both high premiums and price volatility.

This risks to become a catch 22 situation, where the Datagen network is not scaling because is expensive and is expensive because is not scaling.
To solve this problem, is necessary to off-load part of the price from the Users’ shoulders. It’s necessary to subsidize the price, so that users pay part of it, but not all of it. 
In this way a positive-feedback-loop can start: users with a willingness to pay lower premium prices are on-boarding the network, creating the demand for an higher number of validators and creating a more geographically diverse user base and all the other premises so that validators must compete to offer sustainably lower prices, able to equate or even outperform centralized solutions’ prices, without the aid of the subsidies used necessarily in the early phases, to go there. 
Given that the Datagen network is operating in synergy with the crypto industry, the solution is not far-fetched: although of dubious environmental sustainability, PoW blockchains have demonstrated that mining inflationary incentives are enough to nurture a globally distributed and colossal energy-devouring data mining industry. 
Traditional PoW mining industry relies just on inflationary mined tokens (and on transaction fees), while in the Datagen network the main source of revenue for the validators is the computational power provided to and paid by the Users, but, at the same time, inflationary mined tokens can provide additional revenue, allowing validators to charge the Users a lower price. 
Being the Heavy Blockchain a Parachain that can use a very computationally light PoS consensus protocol kept safe by the Polkadot Rely Chain, there is no need to waste computational resources to PoW-mining data to secure and hash transactions in the Datagen network, but it is possible to borrow from PoW a basic principle: in PoW miners are basically rewarded by increasing their probability to win inflationary-mined tokens while they proportionally increase their relative contribution to the hash rate of the network. 
In the same way, a very simple mining/validating reward mechanism can be introduced for the Datagen network, replacing the hash rate variable with the total-computing-power-processed-by-the-network variable. 

That, very simply, looks like: #DGr_A time = #DGr_tot time / (Comput_tot Network time / Comput_A time)
#DGr is inflationary reward in DataGen tokens. #DGr_A time is the reward to the individual validator in n time. #DGr_tot time is the total inflationary release in n time. Comput_tot network is the computational power processed by the network in n time. Comput_A is the computational power provided by the single validator in n time.


Another important utility of the DataGen token is that Datagen network’s validators need to buy it in advance and stake it (to be admitted as validators) and if they are found cheating (in reason of the cross-check process described above) they have to pay a price, losing coins that they are staking and eventually losing them all and being expelled from the network. 
In this way, setting a very high price for providing false computation, it is possible to keep the percentage of cross-checks to a minimum, compared to the total amount of computations processed by the Datagen network, and to keep as low as possible the computational power consumed by the cross-check process itself.

This simple token reward can be a very valuable addition to secure the affordability of the DataGen network and the staking functions of its security,  but is valuable only as long as the DataGen token is an asset with an economic value and whose value is projected to grow or to stabilize (not to decline) long term-wise. 

To achieve the result of preserving the economic value of the DataGen token, is necessary for the DataGen token supply to be limited and known and so is its inflationary rate (at least its possible range). 

For this reason, the DataGen token, which is already existing as a BEP-20 on BSC ( 0x2c57b5570bd663ae32ae01c34a01DEB3fEEd4A5d ), has a limited supply of 30M (30,000,000.eighteen decimals) #DG, all minted. 
While half of the supply is reserved for other scopes (listing, treasure, crowdloans, community programs, etc.), the other half (15,000,000.eighteen decimals #DG) is held safe by a solidity smart contract (0x2c57b5570bd663ae32ae01c34a01DEB3fEEd4A5d ), already created, funded and audited. The smart contract ( https://github.com/Datagen-Project/DataGen-Smart-Contracts/blob/main/contracts/MiningReservation.sol ) will start to release #DG tokens on the 1st of April 2024 (a date far enough to have the Datagen network to be developed and running) at a rate of 4560 #DG per day. 
The release rate will halve every 1095 days, until a minimum release rate of 71.25 #DG per day is achieved, after 6 halves (or 6570 days from the first inflationary release). 
The relatively small amount of ≈71 #DG per day will go on until the funds inside the smart contract are exhausted: 216 years after April 2024, in the year 2240. 

The halving mechanism will allow the inflationary effect to be much higher in the first years of operation of the Datagen network.

Since the first years of inflationary rate could potentially harm the capability of the token to retain financial value, and so to be an adequate monetary incentive for the validators, especially in bearish market-cycles of the crypto economy, in the MiningReservation.sol smart contract is already imbedded a procedure in which users can pool 100K #DG tokens to request a voting and in which, subsequently, any token holder can stake and vote with 20 #DG or more, so that the inflationary rate is lowered (burning a percentage of the inflationary tokens, as stated in the voting proposal). 
The high number of tokens required to be pooled to start the vote is ensuring that preposterous voting proposals are much more unlikely, while the vote (with a minimal and maximal duration indicated in the smart contract) will have the important role of balancing the need of keeping the cloud computing processed by the Datagen network affordable, with the need of having a DataGen token able to retain financial value.


The Datagen token is an essential addition to the Datagen ecosystem, to help promote both a more decentralized validating stack (more bare-metal or regional validators) and an increased affordability of the computational power provided by the network and to keep secure and reliable the validating activity, by making possible low-computing consuming cross-checks. 
All this is coupled with community-owned and community-operated features that are helping to keep decentralized the DataGen token itself.








**Where Datagen can fit in the Metaverse and where off-chain computation can help**

For example, let’s imagine how the computational needs could be addressed in the future for a decentralized metaverse{43} like Decentraland{44} or The Sandbox{45}, understanding how it is working right now. 
As of now, you have users interacting with the game environment and with other users through a gaming graphic interface that is processed by centralized providers like AWS, but the game can also act in a way that allows specific front-end interactions with on-chain stuff. 
For example, when the user’s character is moving in a room in the game, he is interacting with a server that is computing all the complex interactions happening in the online game, between user and user and user and environment, while the user’s device is also making use of a local graphic card to allow him to “see” all the interactions. In the case of the Sandbox the server is outright hosted by AWS{46,47}, while, in the case of Decentraland you have a slightly more complex and decentralized system in which you have different server providers, called catalysts, that, while reducing centralization risks because of their redundant number, are, in last resort, presumably hosted by AWS {48,49,50}. 
Despite the game being branded Web3, none of the interactions that the user’s character is doing are processed on-chain. Only when the user interacts with a special subset of data (for example, he walks his character in front of what he sees rendered as treasure chest) he triggers a set of instructions (that in Decentraland are called “Scene blockchain operations”{51}) that, through smart contracts, are allowing an interaction with the user’s wallet (that he must had previously connected and kept open with a frontend implementation like MetaMask{52}),  allowing him to collect a token reward (for having opened the treasure chest).
It is understandable that a decentralized game is not running on-chain because:
 
a.	No one even attempted to provide cloud computing on-chain in the scale required to operate an online multiplayer metaverse; 
b.	The only things, that, right now, are valuable enough to involve on-chain interactions are digital assets transfers, like NFTs or tokens.

But what is going to happen when metaverse will be a more pervasive reality?
If you care about the human right of keeping a private sphere that a for-profit corporation can access only with your permission, for sure you already think that having your digital assets registered on-chain, vs in a database that Amazon can erase or tamper at will, is a good idea and this is something that decentralized metaverses have already figured out, as explained before. 

But, as a decentralization conscious consumer, do you really think that the ownership of digital assets is the only valuable thing that should be kept under your control (maybe at disposal of law enforcement under judicial order) while you are in a metaverse or in AR / VR? 

Maybe, for the stage of development at which decentralized metaverse is right now, there aren’t enough valuable things to be kept away from the potential misdoings of centralized cloud computing: after all, who cares if my LegolasJoe character is visiting the parcel of land 17th or 19th!? Should I even care if AWS is processing that? Probably not. 
But what about the moment in which the metaverse will be pervasive and advanced enough that you will be able to have a remote consultation with a mental health professional in the metaverse, should I care? Should you care if you are speaking of your political views with friends you met in the metaverse? Should you care when sensitive business information are all flowing in the virtual meetings happening in the metaverse?
Someone may say, “No, of course I’m quite happy to deliver all this information to a for-profit corporation that really cares of my wellbeing”.
For those with this opinion will probably don’t care enough to even on-board decentralized metaverses and will use spend their metaverse time in centralized metaverses, operated by companies like Meta{53} (former Facebook), whose not exactly uplifting track record in terms of transparency in their data management policies, if translated in the Metaverse context could lead to both pervasive surveillance and even to subtle perceptive distortions with the aim of achieving behavioral modifications{54}.
But what about those who entrust their metaverse-time to decentralized options to stay safe from the reach of centralized corporations and that are choosing Web3 over Web2 because they think thatWeb3 is more in line with their ideas of liberty and emancipation? It isn’t going to be limiting and disappointing for them if the only function of “decentralized” metaverses is the decentralization of digital ownership, while all the rest is processed by a server farm owned by AWS or Google? Is this going to make users feel safer than Meta’s metaverse? Is it safer? Won’t this risk that the increasingly conscious decentralization consumers will end up being disillusioned by the marginal role of decentralization and will simply abandon Web3 branded metaverses in favor of flashier metaverses built by Meta or other centralized corporations?
Let’s see how this massive amount of data produced by a decentralized metaverse could be processed in a safer way.
Maybe on-chain solutions like Datagen will be impractical to keep safe the computation of the whole huge number of eye-to-eye interactions happening in the metaverse, given the sheer amount of data and the need for its affordability and speed. This is where off-chain (blockchain based) solutions, still safer than AWS, like Phala{55}, for instance, can come to rescue, going in places that are more impervious to on-chain based solutions, simply aggregating different off-chain sources, and keeping them safe with encryptions and smart contracts. 
But this could be not enough for particularly sensitive data: at the same time, you probably ideally want that the most important stuff is computed on-chain, in a safer way. 



**The future of Metaverse with Datagen**

It’s quite possible that the future will look like a place where on-chain and off-chain computation are working in unexpected synergic ways. 




For example, you could have a tripartite situation in which: 

1.	simple interactions with the environment (for example rendering of buildings that are entering in your field of view while you are roaming in a virtual street, or minigames, or computation of the game physics, etc…) can be computed by aggregating off-chain clouds using smart contracts, and the smart contracts could transparently discard cloud providers that are not respecting certain rules; 
2.	more sensitive interactions (for example conversations with other users or data that users themselves are classifying are sensitive -something like: anything my metaverse character writes or draws in this whiteboard is sensitive) can be computed by a separate -on-chain- provider or, alternatively, an on-chain cloud computing provider could be entrusted in computing the data necessary to generate and maintain a tamper-proof encryption, so that only those with an appropriate key will be able to decipher in a human eye readable those specific interactions happening in the metaverse. 
3.	digital asset ownership transfer is registered on-chain with a mechanism similarly to the one currently used by Decentraland in Scene blockchain operations.

Maybe on-chain computation with the Datagen network will become so efficient and fast that it would be able to do all by itself, but, as history is teaching us, the Internet is becoming an increasingly complex animal{56} with different layers interacting in very complex ways{57}, and the Metaverse will equally be layered, probably in ways that are still difficult to grasp and it’s more probable that the Datagen network will fill a only specific niche in the infrastructure layer{58} of the metaverse itself, maybe in a way that is different from the one imagined by the above paragraph.

In the next 10 to 30 years the cloud computing demand of metaverse (and gaming) will grow exponentially, a certain percentage of it will be decentralized metaverse (and decentralized gaming) and the blockchain-based infrastructures with the most interesting premium qualities will claim a chunk of it: the Datagen network has the right characteristics to be in the winning pool.


**Where Datagen can help PoS blockchains to stay decentralized{59}** 

Hetzner, along with centralized cloud services providers Equinix and Amazon Web Services (AWS){60}, hosted a whopping 65% of Solana’s stake in August 2022. When, in late October 2022, Hetzner (on which ≈40% of Solana validators were hosted) unilateral and suddenly banned{61} ≈1K Solana Validators, the event sparked a discussion{62} in the blockchain community and increased the awareness that an overwhelming concentration of validating activity in the hands of few, centralized providers is a strong strategic risk.
Solana is not alone in this dangerous vulnerability: Polkadot validator set-up{63,64} currently supports only Google Cloud, AWS, Microsoft Azure and Packet. BNB Chain Validator{65} location is not disclosed66, but different public statements of Binance’s core team members{67} revealed partnerships between Binance and Google Cloud to host validators of the BNB chain, suggesting that a strong centralization process is in act, with Google as main provider, at least for institutional BNB nodes. Coinbase Cloud{68}, a foundamental piece of infrastructure for the crypto industry, where are kept huge pools of 25+ major cryptocurrencies, is practically running solely on AWS and AWS’ tools{69}. Figment network{70}, one of the main infrastructure providers for validators, nodes and staking pools is running mostly on AWS, Google Cloud and Digital Ocean{71}. 53% {72} of Ethereum Mainnet nodes{73} are hosted by AWS and, with the Ethereum Merge in Ethereum 2.0, this could become a single point of failure{74}, with AWS and other few providers{75} able to shut down the Ethereum network at will. Cardano{76} seems less vulnerable{77,78} than his peers, in this regard, since its validators are “just” 19.5% hosted by AWS, but the percentage balloons to a staggering 53.6% once you factor the 5 biggest providers (in order AWS, Digital Ocean, Hetzner, Contabo gmbH and Google Cloud), revealing, to a closer look{79}, that not even Cardano is safe. 


The Datagen network could become the network of choice to source cloud computing for many PoS blockchains  (in particular once Datagen is  interoperable with IPFS and/or Filecoin for storage functions), being the only decentralized cloud computing player that is putting so much attention in designing proper incentives to decentralize its network, instead than being just another additional layer running over AWS, while Datagen can keep efficiency levels just slightly lower the ones of centralized providers.




**Where Datagen can help DeFi to stay decentralized**

All DeFi applications based or reliant on PoS protocols are at risk of failure because of excessive centralization potentially leading to single points of failure due to censorship, etc… The Datagen network can help them to stay decentralized in the same way in which it can help PoS blockchains. In the same fashion, the Datagen network can be a more resilient cloud computing provider for off-chain (but Web3 related) DeFi applications.



**Where the Datagen network could help privacy-friendly search engines to be more decentralized**

Privacy friendly search engines like DuckDuckGo, Mojeek, Qwant, Swisscows, etc… , but even the Web3-based Brave Browser, are either running on AWS / Azure (DuckDuckGo, Qwant{80}, Brave{81}) or self-hosting everything with great efforts (Swisscows{82}, Mojeek{83}). A trustless, secure decentralized computational network could greatly benefit them in sourcing cloud computing in a way that is at the same time scalable and respectful of their mission.



**How the Datagen infrastructure can benefit from the image rendering industry**

Image rendering represents one of the cloud computing industry segments more heavily targeted by peer decentralized cloud computing projects. The first use-case that the blockchain computation veteran Golem Network tried to tackle has been rendering and another major project is so focused on the image rendering segment that is called Render Network{84}. 

Why?

1)	Image rendering is a big and fast-growing segment of the cloud computing industry{85}; 
2)	Image rendering is processed mostly with GPU, and GPU supply can be easily found both in gamers’ hardware (exploited by opportunistic networks like Massive Computing{86}) and in ETH -and other POW protocols- professional miners’ hardware); 
3)	Image rendering is really forgiving in terms of latency time requirements (for a 3D artist is ok to wait seconds and even a couple of minutes to see an image rendered) and this makes the rendering segment particularly suitable for the projects that are struggling with technical weak latency performances, making it a low-hanging fruit. 
4)	For the same reasons, image rendering is a segment in which the Datagen network can easily become a relatively relevant player, given the easier technical requirements, but also a segment over which many birds are already flying and competing, making it for Datagen a welcome additional use-case, but one in which Datagen can hardly become a dominant player.




***Relationship with Web2 applications**

The Datagen network is born in the context of blockchain and Web3, but there are plenty of Web2 applications for which the Datagen network can offer huge plus, compared to traditional centralized providers: let’s think of NGOs online activities, always at risk of censorship in non-democratic countries, or machine learning startups, in constant need of reliable, uptime improved and cheaper GPU computational power for their AI.


The Datagen network will be more useful for specific segments and less useful for others. But at the same time, it will be able to solve specific problems related for specific industry segments in need of safe, on-chain efficient computation, innovating from and exceeding their performances and, in the process, it can greatly aid Web3 to stay and grow secure.



Paraphrasing “The Dark Knight” **The Datagen Infrastructure may not be the Decentralized Cloud Computing Infrastructure that the World deserves, but the one it needs now.**

By choice we didn’t include many coding functions in the Whitepaper 2.0, since code can always change, be improved, or updated. To follow the evolving development, visit the Project’s GitHub https://github.com/Datagen-Project and feel free to contact us if you want to contribute.


Sources
 

1https://drive.google.com/file/d/19F8vn1nuF2Sotoml61RKaiIIfR_iDQq2/view
2https://open.library.okstate.edu/introphilosophy/chapter/ship-of-theseus/
3https://computertech.com/blog/difference-cloud-storage-computing
4https://docs.filecoin.io/about-filecoin/what-is-filecoin/
5https://ipfs.tech/
6https://bitcoin.org/bitcoin.pdf 
7https://ethereum.org/en/whitepaper/  
8https://thepaypers.com/expert-opinion/ftx-is-not-a-crypto-failure-but-a-centralisation-failure-learnings-from-the-ftx-collapse—1259308 
9https://assets.kpmg/content/dam/kpmg/ie/pdf/2022/04/ie-blockchain.pdf 
10https://arxiv.org/pdf/2203.03717.pdf
11https://adan.eu/en/article/blockchain-protocol-energy-footprint
12https://www.hindawi.com/journals/scn/2021/8363131/ 
13 https://blog.massbit.io/the-need-for-blockchain-data-propagation/ 
14 https://vedveethi.co.in/eNote/BlkChain/Unit-2/BlkChain_Unit-2_0060.htm 
15https://aleph.im/#/ 
16 https://sonm.com/ 
17https://www.ledger.com/academy/layer-2-blockchains-explained 
18https://climbtheladder.com/10-layer-2-network-design-best-practices/ 
19https://www.web3.university/article/sidechains-vs-layer2s 
20https://www.alchemy.com/overviews/sidechains-vs-layer2s  
21https://www.blocknative.com/blog/monitor-polygon-mempool
22 https://thedefiant.io/polygon-true-layer2
23https://medium.com/@gertrammeloo/the-economics-of-the-proof-of-stake-consensus-algorithm-e28adf63e9db 
24https://arxiv.org/pdf/1809.00455.pdf 
25https://handbook.golem.network/ 
26 https://stats.golem.network 
27https://docs.akash.network/
28https://docs.cudos.org/docs/learn/introduction/overview 
29https://www.cryptoninjas.net/2020/03/13/decentralized-cloud-akash-interoperating-with-solana-for-hyper-performance-smart-contracts/
30https://akash.network/blog/akash-partners-with-solana-to-bring-web-scale-smart-contracts-to-supercloud   
31 https://coinrivet.com/it/amazon-hosts-37-of-actively-staked-sol-could-this-be-a-solana-kill-switch/ 
31https://docs.oortech.com/oort/oort#what-is-computecoin
32https://computecoin-network.s3.ap-southeast-1.amazonaws.com/static/ComputeCoin_Whitepaper.pdfv
33https://en.bitcoin.it/wiki/Common_Vulnerabilities_and_Exposures
34 https://www.climatiq.io/blog/measure-greenhouse-gas-emissions-carbon-data-centres-cloud-computing#:~:text=Global%20emissions%20from%20cloud%20computing,that%20fuel%20our%20global%20economy. 
35https://uptimeinstitute.com/resources/research-and-reports/uptime-institute-global-data-center-survey-results-2022
36https://cosmos.network/intro 
37https://substrate.io/ 
38https://docs.substrate.io/reference/frame-pallets/ 
39https://wiki.polkadot.network/docs/learn-parachains
40https://www.futuremarketinsights.com/reports/gpu-as-a-service-market#:~:text=Prominent%20players%20in%20the%20GPU,Technologies%20Ltd.%2C%20among%20others 
41https://www.globalpetrolprices.com/electricity_prices/ 
42https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-gpu.html 
43 https://nftplazas.com/virtual-blockchain-worlds/
44https://play.decentraland.org/?realm=artemis&position=1%2C0&island=I4gcu 
45 https://www.sandbox.game/en/ 
46https://www.twobirds.com/en/insights/2022/global/the-sandbox-and-the-metaverse#:~:text=The%20Sandbox%20platform%20is%20a,hosted%20on%20Amazon%20Web%20Services 
47 https://zebpay.com/blog/what-is-sandbox-complete-guide 
48 https://github.com/decentraland/catalyst/issues/539 49https://decentraland.github.io/catalyst-monitor/  50https://github.com/decentraland/catalyst-owner 
51 https://docs.decentraland.org/creator/development-guide/scene-blockchain-operations/ 
52 https://metamask.io/ 
53 https://about.meta.com/what-is-the-metaverse/ 
54https://www.washingtonpost.com/technology/2022/01/13/privacy-vr-metaverse/  
55https://wiki.phala.network/en-us/general/phala-network/intro/ 
56https://groups.csail.mit.edu/ana/Publications/PubPDFs/Complexity%20of%20Internet%20Interconnection%20TPRC%202007.pdf
57https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm
58https://www.parcl.co/blog/the-seven-layers-of-the-metaverse  
59https://blockworks.co/news/measuring-decentralization-is-your-crypto-decentralized
60https://medium.com/coinmonks/running-a-solana-validator-on-aws-bb86162eaf29
61https://cryptopotato.com/cloud-provider-bans-solana-nodes-taking-40-offline/
62https://decrypt.co/113429/is-solana-decentralized-cloud-provider-hetzner-ban-raises-questions
63https://wiki.polkadot.network/docs/maintain-guides-how-to-validate-polkadot 
64  https://guide.kusama.network/docs/maintain-guides-how-to-use-polkadot-validator-setup/
65https://www.bnbchain.org/en/staking
66https://github.com/bnb-chain/bsc/issues/243
67https://twitter.com/cz_binance/status/1588949895985393664?s=21&t=LCdi7tZFKOxq1p3uLmkfeQ
68https://www.coinbase.com/cloud
69https://aws.amazon.com/machine-learning/customers/innovators/coinbase/
70https://www.figment.io/infrastructure
71 https://www.figment.io/resources/full-disclosure-figments-cosmos-validator-infrastructure 
72https://cointelegraph.com/news/ethereum-dev-addresses-node-centralization-concerns-in-runup-to-the-merge
73https://www.ethernodes.org/networkType/Hosting
74https://hackernoon.com/ethereum-20-staking-on-aws-cloud-staking-matters
75https://cryptoslate.com/data-center-operator-hosting-17-of-ethereums-nodes-says-staking-is-not-permitted/
76https://www.coinbase.com/it/cloud/discover/protocol-guides/guide-to-cardano
77 https://medium.com/poapool/cardano-da-holders-strategy-how-to-choose-stakepools-e2946f87b1f8 
78https://developers.cardano.org/docs/operate-a-stake-pool/ 
79https://datastudio.google.com/reporting/3136c55b-635e-4f46-8e4b-b8ab54f2d460/page/p_zgx5s2okoc
80https://news.microsoft.com/europe/features/qwant-and-microsoft-announce-an-exclusive-partnership-for-a-unique-internet-research-experience/#:~:text=Microsoft%2C%20for%20its%20part%2C%20provides,services%20and%20Bing's%20algorithmic%20research
81https://himalayas.app/companies/brave/tech-stack
82https://www.realwire.com/releases/Google-alternative-Search-engine-Swisscows-starts-selling-shares
83https://blog.mojeek.com/2020/12/frequently-asked-questions-about-mojeek-search-engines-technology-stack.html
84https://rendertoken.com/
85https://www.prnewswire.com/news-releases/visualization--3d-rendering-software-market-size-is-projected-to-reach-usd-3083-9-million-by-2027--at-a-cagr-of-12-7---valuates-reports-301452665.html  
86 https://www.joinmassive.com/ 
 
 
 


