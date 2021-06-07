```
 _ __ _ ____ _  _ ____ ___  ____ ____
 | | \| ==== |__| |--< |__> |--| [__]

```

# Insurdao Token Economics and Mechanisms


## Abstract

The InsurDAO Protocol allows companies and communities to create a self-insurance autonomous organization by leveraging collateral assets approved by the "InsurDAO Governance". InsurDAO Governance is the community responsible for managing various aspects of the InsurDAO Protocol. xDST [debt solvency token] is a decentralized collateral-backed cryptocurrency soft-pegged to any FIAT currency, as authorized by the InsurDAO Governance and selected by the respective mutual group. xDST offers the flexibility and trust to organically create a TPA (Third Party Administration) network of service providers, offering them an tokenized obligation with automatic and instant redemption. 


## Decentralized Insurance


P2P insurance companies have evolved through three waves.

* Wave 1: The distribution model, where small groups with similar risk levels self-insure their deductibles to lower their premiums.
* Wave 2: The carrier model involves the same small groups sharing the risk of insurance by paying premiums jointly. If there is money left unclaimed by the end of the year, members get to share the remaining funds as a payback.
* Wave 3: Self-governing P2P insurance brings the process closer to the ideal of mutual insurance. 

InsurDAO protocol an evolution of the Wave 3, including a full spectrum of incentives for its different stackholders.


## Automonous Actuarial Calculations

Mutual policies will be managed by adaptive algorithms that will seek to maintain the basic function of an imdenization minimum function. Balancing between the premium price, frequency and payout caps, the algorithm will self adjust constantly to optimize the cashflow reserves while maintaining a feasible premium price for its memebers. Different models will be deployed by the governance, and Brokers will be able to create several different products based on the calibration of the model he chooses i.e. a model that self adapt with a fixed and immutable coverage price, but with a dynamic premium payemnt based on low cashflow triggers, that will start an apportionment, indenpendent of the monthly or yearly payment. This model is suitable for groups that have a high level of trust and are willing to collaborate in any scenario, because the level of engagenment they have between each other. New models will be deployed to the system in order to cover different kinds of P2P engagenment, trust, willing to take risk, and other interesting behaviour factors to build a so wished [nash equliibrium](https://www.investopedia.com/terms/n/nash-equilibrium.asp#:~:text=The%20Nash%20equilibrium%20is%20a%20decision-making%20theorem%20within%20game,the%20decisions%20of%20other%20players.) game, between non-fully cooperative players.


[show formula here]


## xDST Stable Coin

Stability is provided by a peg to a known stable coin, and will be used by communities and companies to
distribute credit to members. These credits serve as payment for services within the TPA (Thirdy Party
Administration) network. After receiving payment in XDST, TPA professionals can redeem them with the main vault.

Our protocol comprises incentives, rules, and interfaces such that agents in our system, whom we do not control, self-organize in a way that fulfills the purpose of our protocol, i.e. to self-insure.

We will generate the expected utility (values for a particular choice or outcome) using ABM [Agent Based Modeling]

The direct goals of the insurDAO network are --
- maintain cashflow adequate for stable solvency
- prevent fraud
- process member claims fairly.


## Governance


### What is INSR ?

INSR is the governance token and solvency recapitalization of the InsurDAO
Protocol.


> INSR as governance token

Using NFT to represent the reputation, decisions are made by a reputation weighted vote. Governance token will be staking, and part of the tokens will be used to cover losses in unssuccessful decision. The idea of using a double token solution for governance can solve flash loan atacks that exploit the voiting weights, so only those who owns both, the NFT representing his reputation plus a weighted quantity of tokens, will be able to approve and disaprove proposals. 



> INSR as a solvency recapitalization

In case any policy that suffers a failure in the risk calculation system, or
it's stable coin becomes compromised, INSR will be used to cover part of the
incurrent losses. The cap for losses coverage are until 20% of the total cap.


## INSR tokens minting and burining

INSR are created with a fixed supply, but with a dynamic distribution.


## INSR Distribution

Robust governance includes a large and decentralised stakeholder-base. A single entity or a small group of closely aligned entities would centralise mStable and potentially create a dangerous single point of failure. Notice that the airdrop distribution has [SEC limitation](https://www.sec.gov/litigation/admin/2018/33-10530.pdf)

> Genesis Distribution
Bootstrapping the network at inception, including a base of users, network operators (if applicable), developers or third-parties, and market participants. Incentivize ‘skin-in-the-game’ amongst token holders

**TOKEN SALES**
- Sell future services
- Solicit investments in the project
  1. First private sales
  2. Second public sales

**INTERNAL ALLOCATIONS**
- Founders
- Developemnt Fund
- Ecosystem Fund 
- Advisors


> Ongoing Distributions

**PASSIVE AIRDROP**
Tokens allocated allocated automatically to public participants at zero or nominal cost without their active participation, often based on other cryptoasset holdings.

- Distribute tokens to interested parties
- Market a project amongst broad user groups

**INTERACTIVE AIRDROPS**
Tokens allocated at no cost to public participants based on active participation or claims process.
- Market a project to targeted potential user groups




## INSR Holders responsabilities


- Approve new policy templates.
- Determine the total payout minimum and maximum
- Premium price maximum and minimum
- Incentivation for good and bad behaviour of stakeholders.
- For failed systems, use the InsurDAO tokens to cover the losses. 
- Auto increase and decrease risk factors for adaptive policy learning.
- Receive incentives for succesfull models, and pay penalties for failed models.
- Add a new collateral asset type with a unique set of Risk Parameters.
- Change the Risk Parameters of one or more existing collateral asset types,   because even that they are stable coins for the first phase, will setup the % of the collateral
- Change the Policy templates risk parameters
- Create new Policy templates
- Rank TPA Brokers, if they are getting good discount in building the TPA.
- Connect mutual cashflow with automated lending pools.
- Choose the set of Oracle Feeds.
- Choose the set of Emergency Oracles.
- Trigger Emergency Shutdown.
- Upgrade the system.
- Establishing risk assessment standards for onboarding new Collateral and Policy types
- Communicate publicly about their views on the various issues that INSR governance is addressing at any given time


Voicing opinions and the reasoning behind them, including serious participation in forum discussions, is important because of the public and decentralized nature of the protocol and its governance.



## INSR Holders Rights

INSR holders have the ability to enact technical changes to the Maker Protocol itself and also to ratify decisions on-chain about non-technical matters.
Whether that be a change to the system parameters, or a decision to accept a new governing philosophy, INSR voters have ultimate control.

INSR holders who are interested in actively participating in the management of the InsurDAO can visit the TODO: Voter Onboarding Guide for an overview of how to get started.


## INSR as a collateral

If INSR is being used as a Collateral of first resort i.e. as a collateral type locked in Mutual Policies, then it would take away from its effectiveness as a Collateral of last resort. A negative feedback loop would occur in a scenario when a falling MKR price would trigger the liquidation of INSR-collateralized Mutual vaults, further causing downward pressure on INSR price.


## Governance Staking

This is the current implementation of INSR staking, and went live at .......  . 
Once a INSR  holder locks their tokens in the staking contract and begins voting on proposals they become a Governor. 
Longer staking lockups result in higher staking returns (in INSR) and higher voting weights (i.e. the longer you stake, the more skin in the game you have. 
Because of this, the longer you stake, the more power the user has over the vote)


## Who Should join InsurDAO
A large different class of stakeholders will be able to participate. To encourage or discourage behavirours, we will annotate in which different behavirours we will give or retain tokens. 

[i] = recieve token incentives
[p] = pay token as punishment 


#### Freelancers
- Get paid for work on InsurDAO projects you propose
- Develop Solidity, Javascript/Typescript
- Create online content
- Produce local events

#### Actuaries
- Experiment with a new form of governance
- Take part in daily governance decisions
- Create new products and risk models [i]
- Receive royalties for the successful products popularity [i]
- Approve or reject new products created by others
- Capped indenization for non successful models. [p]

#### Regulators
- Tag claims as fraud without false positives
- - Qualify claim-ajusters. They can stake wepy tokens and receive premium for the stake for the job of supervise the payouts in the DAO.

#### Brokers
- Create new self-insurance communities  [i]
- Sell self-insurance back-office for existing companies [i]
- Collaborate bringing new members and creating new groups [i]


#### Claim Adjusters
We will stake bonuses to claim-ajusters, and this bonus will be locked, during the time he works for the group. In case he cheats, we take him out the bonus to pay the liqudity providers. Claim ajuster will have a reputation rank, based on retulators and members feedbacks. We could stake automatically 50% and lock, and depending on the track record we release, or we can make big premium staking for the good service he provides to the network.
- We will stake bonuses to claim-ajusters, and this bonus will be locked, during the time he works for the group. In case he cheats, we take him out the bonus to pay the liqudity providers. Claim ajuster will have a reputation rank, based on retulators and members feedbacks. We could stake automatically 50% and lock, and depending on the track record we release, or we can make big premium staking for the good service he provides to the network.
- Correctly pays the claims.
- Defect paying fraudsters.
- Defect frauding the system: for this the stacked/locked bonus will grow in every good paid claim.
- Better reputation will lead to better payment per claim.
- Correctly pays the claims.
- Defect paying fraudsters.
- Defect frauding the system: for this the stacked/locked bonus will grow in every good paid claim.
- Better reputation will lead to better payment per claim.


#### TPA
- Offer your service in the market place
- Receive benefits and bonuses over your good work and reputation


#### Liquidity Providers
- Lock capital to secure solvency into existing DAO groups and receive preimum [i]
- Stake the locked capital [i]

#### Mutual Insured
- Receive a protection from the mutuality, and can contribute for the main vault or no. 
- If members are receiving a benefit from a company, the company will be the responsible to create the liquidity to be available for its members, but if members of a community are building their own pool, they will be the ones contributing to the main vault.
Community Pools
- Receive bonuses for TPA refferals 
- Collaborate avoiding to register new claims, receive good behaviour tokens. [i]
- Pay good behaviour tokens when starting a new claim. [p]

#### TPA Audit
Auditors will buy [or receive as bonus] TPA tokens to white list or black list TPA service providers, and also will audit their transactions. We will stake their tokens, and in case we find frauds that TPA couldn't detect, we apply a penalty over the staked TPA tokens. Auditors that succeed to maintain a good track record will receive TPA tokens bonus.
- Receive reputation token for auditing TPA
- Search for fraud 
- check TPA for fraud
- pay TPA-token for failed cases
- receive w-token for good performance



## INSR Token Supply

There were a total of 1,000,000 INSR at the inception of the Maker Protocol. To find out how much INSR currently exists, see the INSR Token Contract on Etherscan. [TODO: add link]
The total number of INSR in existence can fluctuate based on how the system runs. For instance, the total supply of INSR can increase if the system is running a deficit and needs to dilute INSR as a recapitalization source.
If the system is governed well, the total amount of INSR will decrease as MKR is destroyed in exchange for excess xDST from the system’s surplus.


## Policy Rules

* PAYOUTS
  - Maximum Contribution cannot exceed [x] of payer's available balance


* MEMBERS
  - will have a limited number of sereial claims, based on a progressive rule,
     like: two first claims can have a 3 days space, but the third claim only
     after a week. When this member pauses the claim requests, after 1 month, we
     reset his claim space.

* CASHFLOW RISK:
  - a good track record will pay less premium for reinsures
  - only groups with a minimum track record standards will be able to publish
     their groups for reinsurance. Qualitative factors will also be used to rank
     the group reliability, like: claim-ajuster reputation.

* RISK:
  - Auto-reduction of Risk by [x] after [y] claim-free months
  - Auto-increase of Risk by [x] after a claim
  - Recalibrate the system if an unexpected claim size/frequency happens.

## Emergency Shutdown

Every mutual group can have all the asset redistributed for their members, and
part of the funds guaranteed by the governance token.




## Blockchain Advantages

- Zero bureaucracy to start a new pool
- Track TPA payments
- Claim managed by Digital Signatures
- Instant Settlements
- Near zero transaction costs [using layer2]
- Business rules enforcement by smart contracts
- 100% ledger transparency between the pool players
- Automatic crowdfunding facilities for reinsurance
- Decentralized Governance
- Solvency vault protection
- Automatic distribution of incentives for contributors [refferals, claim adjusters]


## Roadmap


## Team
* [Henry Hazan](https://www.linkedin.com/in/henry-hazan-77b94116/) - CTO
* [Leonardo Diamante](https://www.linkedin.com/in/leonardo-diamante-84a4003b/) - Chief Actuary
* [Israel Gottlieb Phd](https://www.linkedin.com/in/israel-gottlieb/) - Machine Learning
* [Yosef Kulikowsky](https://www.linkedin.com/in/yossef-kulikowsky-2b547b14a/) - Full Stack Programmer


## Disclaimers
[TODO]


## Resources

* [token-distribution-mechanisms](https://smithandcrown.com/research/introduction-to-token-distribution-mechanisms/)
* [mina-token-distribution](https://minaprotocol.com/blog/mina-token-distribution-and-supply)
* [maker-dao](https://community-development.makerdao.com/en/learn/governance/mkr-token/)
* [maker-dao-voting-onboarding](https://community-development.makerdao.com/en/learn/governance/how-voting-works/)
* [P2P-insurance](https://www.moneyunder30.com/p2p-insurance)
