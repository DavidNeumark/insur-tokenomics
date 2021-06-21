```
 _ __ _ ____ _  _ ____ ___  ____ ____
 | | \| ==== |__| |--< |__> |--| [__]

```

# Insurdao Token Economics and Mechanisms


## Abstract

The InsurDAO Protocol allows companies and communities to create a self-insured, autonomous organization by leveraging collateral assets approved by the InsurDAO Governance. InsurDAO Governance is the community responsible for managing various aspects of the InsurDAO Protocol, including xDST. xDST [debt solvency token] is a decentralized, collateral-backed cryptocurrency soft-pegged to any FIAT currency, as authorized by the InsurDAO Governance and selected by the respective mutual group. xDST offers the flexibility and trust to organically create a TPA (Third Party Administration) network of service providers, offering them tokenized obligation with automatic and instant redemption. 



## Decentralized Insurance


P2P insurance companies have evolved in three waves.

* Wave 1: The distribution model, in which small groups with similar risk levels self-insure their deductibles to lower their premiums.
* Wave 2: The carrier model, in which the same small groups share insurance risk by paying premiums jointly. If there is money left unclaimed at the end of the year, members share the remaining funds as a payback.
* Wave 3: Self-governing P2P insurance, which brings the process closer to the ideal of mutual insurance. 

InsurDAO protocol is an evolution of Wave 3, including a full spectrum of incentives for its various stakeholders.


## Automonous Actuarial Calculations

In the InsurDAO protocol, mutual policies are managed by adaptive algorithms that seek to maintain the basic components of an indemnification minimum function. Balancing the premium price and frequency and payout caps, the algorithm constantly self-adjusts to optimize the cash flow reserves while maintaining a feasible premium price for its members. Different models are deployed by the governance, and brokers can create various products based on the calibration of their chosen model. The models self-adapt and offer a fixed and immutable coverage price but a dynamic premium payment based on low cashflow triggers that initiate apportionment, independent of the monthly or yearly payment. This model is suitable for groups that have a high level of trust and are willing to collaborate in any scenario due to their mutual level of engagement. New models are deployed in the system in order to cover different kinds of P2P engagement, trust, risk aversiveness, and other interesting behavior factors to build a game between players who are not fully cooperative.

[p2p-formula]


## xDST Stable Coin

Stability is provided by pegging to a known stable coin and is used by communities and companies to distribute credit to members. These credits serve as payment for services within the TPA (Third Party Administration) network. After receiving payment in xDST, TPA professionals can redeem payment in the main vault.

Our protocol is comprised of incentives, rules, and interfaces so that agents in our system, whom we do not control, can self-organize in a way that fulfills the purpose of our protocol, i.e. to self-insure.

We generate the expected utility (values for a particular choice or outcome) using ABM [Agent Based Modeling].

The direct goals of the InsurDAO network are to: 
- Maintain cash flow adequate for stable solvency
- Prevent fraud
- Process member claims fairly



## Governance

### What is INSR?

INSR is the governance token and solvency recapitalization of the InsurDAO Protocol.


> INSR as a Governance Token

Using NFT to represent reputation, decisions are made by a reputation-weighted vote. The governance token is staked, and a portion of the tokens are used to cover losses in unsuccessful decisions. Using a double token solution for governance can prevent flash loan attacks that exploit the voting weights. Only those who own both the NFT representing reputation plus a weighted quantity of tokens are able to approve and disapprove proposals. 



> INSR as a Solvency Recapitalization

If a policy suffers a failure in the risk calculation system or its stable coin becomes compromised, INSR will be used to cover part of the incurrent losses. The cap for loss coverage is up to 20% of the total cap.


## INSR Token Minting and Burning

INSRs are created with a fixed supply but dynamic distribution.


## INSR Distribution

Robust governance includes a large and decentralized stakeholder base. A single entity or a small group of closely aligned entities would centralize the governance token and potentially create a dangerous single-point-of-failure. Notice that the airdrop distribution has [SEC limitation].(https://www.sec.gov/litigation/admin/2018/33-10530.pdf)

> Genesis Distribution
Bootstrapping the network at inception, including a base of users, network operators (if applicable), developers or third parties, and market participants incentivizes ‘skin in the game’ among token holders.

**TOKEN SALES**
- Sell future services
- Solicit investments in the project
  1. Private sales first
  2. Public sales later

**INTERNAL ALLOCATIONS**
- Founders
- Development Fund
- Ecosystem Fund 
- Advisors


> Ongoing Distributions

**PASSIVE AIRDROP**
Tokens are allocated automatically to public participants at zero or nominal cost without their active participation, often based on other crypto-asset holdings.

- Distribute tokens to interested parties
- Market a project to broad user groups

**INTERACTIVE AIRDROPS**
Tokens are allocated at no cost to public participants based on active participation or claims process.
- Market a project to targeted potential user groups




## INSR Holder Responsibilities


- Approve new policy templates
- Determine the total payout minimum and maximum
- Determine premium price maximum and minimum
- Incentivize for good stakeholder behavior 
- For failed systems, use the InsurDAO tokens to cover loss 
- Auto increase and decrease risk factors for adaptive policy learning
- Receive incentives for successful models and pay penalties for failed models
- Add new collateral asset types with unique sets of risk parameters
- Change the risk parameters of one or more existing collateral asset types (even though they are stable coins for the first phase, it will setup the percentage of the collateral)
- Change the policy template risk parameters
- Create new policy templates
- Rank TPA brokers
- Members who help grow the TPA network receive a discount on TPA services
- Connect mutual cashflow with automated lending pools
- Choose Oracle feed sets
- Choose emergency Oracles sets
- Trigger emergency shutdown
- Upgrade the system
- Establish risk assessment standards for onboarding new collateral and policy types
- Publicly communicate views on various issues that INSR governance is addressing at any given time

Voicing opinions and the reasoning behind them, including serious participation in forum discussions, is important because of the public and decentralized nature of the protocol and its governance.



## INSR Holder Rights

INSR holders have the ability to enact technical changes to the maker protocol itself and also to ratify decisions on-chain about non-technical matters.

Whether it be a change to the system parameters, or a decision to accept a new governing philosophy, INSR voters have ultimate control.

INSR holders who are interested in actively participating in the management of InsurDAO can visit the TODO: Voter Onboarding Guide for an overview of how to get started.


## INSR as Collateral

If INSR is used as collateral of first resort, i.e. as a collateral type locked in mutual policies, then it would decrease its effectiveness as collateral of last resort. 

Our minted stable coin based on the collateral will be used to redeem the collateral giving TPAs confidence in the value of their payment. They are also monitored by the governance regulation and anti-fraud system.

## Governance Staking

This is the current implementation of INSR staking that went live on .......  . 
Once an INSR holder locks their tokens in the staking contract and begins voting on proposals, they become a governor. 

Longer staking lockups result in higher staking returns (in INSR) and higher voting weights. The longer you stake, the more skin in the game you have. Therefore, the longer you stake, the more power you have over the vote.


## Who should join InsurDAO?
A large, varied class of stakeholders is eligible to participate. To encourage or discourage behaviors, we detail behaviors for which we give or retain tokens. 

[i] = Receive token incentives
[p] = Pay token as punishment 


#### Freelancers
- Get paid for work on InsurDAO projects you propose
- Develop Solidity, JavaScript/Typescript
- Create online content
- Produce local events

#### Actuaries
- Experiment with a new form of governance
- Take part in daily governance decisions
- Create new products and risk models [i]
- Receive royalties for the successful product popularity [i]
- Approve or reject new products created by others
- Capped indemnification for unsuccessful models [p]

#### Regulators
- Tag claims as fraud without false positives
- Qualify claim-adjusters. They can stake InsurDAO tokens and receive premium for the stake in return for supervising the payouts in the DAO.

#### Brokers
- Create new self-insured communities [i]
- Sell self-insurance back-office platforms for existing companies [i]
- Collaborate in recruiting new members and creating new groups [i]


#### Claim Adjusters
We stake bonuses to claim adjusters, and the bonus is locked for the duration of the time in which the claim adjuster works for the group. If a claim adjuster cheats, he/she is not eligible for the bonus paid to liquidity providers. Claim adjusters will have a reputation rank, based on regulator and member feedback. We can either automatically stake 50% and lock that amount depending on the track record we release or enable premium staking for good service provided to the network.

Benefits: 
- Accurate claim payment
-- Connection between reputation and payment per claim

#### TPA
- Offer services in the marketplace
- Receive benefits and bonuses for good work and reputation


#### Liquidity Providers
- Lock capital to secure solvency into existing DAO groups and receive premium [i]
- Stake the locked capital [i]

#### Mutual Insurance
- Receive protection from mutuality (option to contribute to the main vault or to opt-out. 
- If members receive a benefit from a company, the company will be responsible for creating the liquidity to be available for its members, but if members of a community are building their own pool, they will be the ones contributing to the main vault.

Community Pools
- Receive bonuses for TPA referrals 
- Collaborate in registering new claims and receive good behavior tokens [i]
- Pay good behavior tokens when starting a new claim [p]

#### TPA Audit
Auditors buy TPA tokens (or receive them as a bonus) to whitelist or blacklist TPA service providers, and also to audit their transactions. We stake their tokens, and if we find frauds that the TPA couldn't detect, we apply a penalty to the staked TPA tokens. Auditors that succeed in maintaining a good track record will receive TPA tokens as a bonus.

- Receive reputation tokens for auditing TPAs
- Search for fraud 
- Check TPAs for fraud
- Pay TPA tokens for failed cases
- Receive tokens for good performance



## INSR Token Supply

There were a total of 1,000,000 INSRs at the inception of the maker protocol. See the INSR Token Contract on Etherscan for the most updated INSR quantity. [TODO: add link]

The total number of INSR in existence can fluctuate based on how the system runs. For instance, the total supply of INSR can increase if the system is running a deficit and needs to dilute INSR as a recapitalization source.

If the system is governed well, the total amount of INSR will decrease as MKR is destroyed in exchange for excess xDST from the system’s surplus.


## Policy Rules

* PAYOUTS
  - Maximum contribution cannot exceed [x] of a payer's available balance


* MEMBERS
  - Members have a limited number of serial claims based on a progressive rule. For example, the first two claims can be made within three days, but the third claim only after a week. When the member pauses the claim requests, we reset his/her claim space after one month.

* CASH FLOW RISK:
  - A member with a good track record will pay a lower premium for reinsures
  - Only groups with minimum track record standards will be able to publish their groups for reinsurance. Qualitative factors such as claim-adjuster reputation will also be used to rank group reliability.

* RISK:
  - Auto-reduction of risk by [x] after [y] claim-free months
  - Auto-increase of risk by [x] after a claim
  - Recalibration of the system if an unexpected claim size/frequency occurs

## Emergency Shutdown

Every mutual group can redistribute the entire asset for their members, including
part of the funds guaranteed by the governance token.




## Blockchain Advantages

- Zero bureaucracy to start a new pool
- Track TPA payments
- Claim managed by digital signatures
- Instant settlements
- Near zero transaction costs [using layer2]
- Business rules enforcement by smart contracts
- 100% ledger transparency between the pool players
- Automatic crowdfunding facilities for reinsurance
- Decentralized governance
- Solvency vault protection
- Automatic distribution of incentives for contributors [referrals, claim adjusters]


## Roadmap


## Team
* [Henry Hazan](https://www.linkedin.com/in/henry-hazan-77b94116/) - CTO
* [Leonardo Diamante](https://www.linkedin.com/in/leonardo-diamante-84a4003b/) - Chief Actuary
* [Israel Gottlieb Phd](https://www.linkedin.com/in/israel-gottlieb/) - Machine Learning
* [Yosef Kulikowsky](https://www.linkedin.com/in/yossef-kulikowsky-2b547b14a/) - Full Stack Programmer


## Disclaimers
[TODO: add disclaimers]



## Resources

* [token-distribution-mechanisms](https://smithandcrown.com/research/introduction-to-token-distribution-mechanisms/)
* [mina-token-distribution](https://minaprotocol.com/blog/mina-token-distribution-and-supply)
* [maker-dao](https://community-development.makerdao.com/en/learn/governance/mkr-token/)
* [maker-dao-voting-onboarding](https://community-development.makerdao.com/en/learn/governance/how-voting-works/)
* [P2P-insurance](https://www.moneyunder30.com/p2p-insurance)
