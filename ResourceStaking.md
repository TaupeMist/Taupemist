# Resource Staking v1.0.0
**Taupemist members can reserve exclusive access to resources.**

### What is Resource Staking?
The resources and assets that belong to Taupemist are limited.
This poses an interesting question in an environment where members have equal rights to use or access those resources.
How can limited resources be distributed fairly and equally amongst members?
The Taupemist organisation does not and will not impose any fees or prices on its members, therefore no price will be established by Taupemist.
In the scenario where one or more members that have equal rights invoke the use of a scarce asset or resource, an exclusivity mechanism will be utilised to fairly resolve any conflicts.

### How does it work?
Taupemist has two main resources available for exclusive use by members, these are bitUSD and USD.
They each represent crypto and fiat respectively, and at any point of time will have equal or similar values.
Many services and features of Taupemist use or require bitUSD and/or USD, and members must ensure that when using
these services/features, that they currently have sufficient exclusivity for the required resources.

Each resource will be accompanied by two pools.
The **first pool**, known as the **Resource Pool**. This will contain the resource itself.
The **second pool**, known as the **Staking Pool**, will contain TMA.
Members seeking exclusivity of resources will do so through the staking of TMA into a position within the staking pool.

Whenever a member seeks to change their staking position (increase or decrease), must submit a staking position request specifying the new position value.

When the member wishes to increase their staking position (the new position exceeds than the member's existing position), then the member is obligated to transfer any additional TMA to meet the new position amount. Conversely, when the member wishes to decrease their staking position (withdraw TMA from their staking position), any excess TMA within their staking position will be deposited into their account.

When a staking position request is submitted, a maturity period of a pre-defined length will begin. The newly updated staking position is not effective or valid until the position has matured i.e the maturity period has concluded.

Once a member's staking position has matured and has been processed, a Resource Staking Summary will be published as a comment on the steem blockchain, at which point they can access the represented resources anytime they wish through Taupemist's services/features.

### How do I submit a staking position request?
##### A staking position request is composed of one single field.
- The __new position__ is the new desired amount of TMA that a member wishes as their staking position.

Through using their desired steem website (i.e. [steemit.com](https://www.steemit.com)), a member can submit a staking position request as a comment to the related post on the steem blockchain.

### What does a Staking Position Request look like?
Here's an example Staking Position Request.
```
### RESOURCE STAKING REQUEST
NEW POSITION: 1 TMA
```

### How long is the maturity period?
The maturity period is **24 hours**.

### What does a Resource Staking Summary look like?
Here's an example Resource Staking Summary.
```
RESOURCE STAKING SUMMARY

STAKING POOL
JIM: 3TMA
JOHN: 2TMA
JANE: 1TMA
TOTAL: 6TMA

RESOURCE POOL
BitUSD: $800
USD: $1000
TOTAL: $1800

PRICE (TMA)
$1800 / 6TMA = $300

PRICE MARGIN (USD)
100 / ($1800 / $300) = 17%
```

### Participation
#### Am I eligible to use this service?
The member must currently possess sufficient TM to comply with the [Taupemist Membership Table.](https://github.com/TaupeMist/Taupemist/blob/master/MembershipTable.md).

#### Is this required?
No, members are not required to participate however in order to have access the resources or assets of Taupemist, the member is required to have a matured staking position of adequate size to allow access to the desired resource/asset.

#### Is there any time limit?
Members may participate until this service is decommissioned.

#### How often may I change my staking position?
As often as desired. The processing duration of each request will be capped at 24 hours and will respect the most recent staking position request for each given member. 

### Key Properties

* ##### A member's staking position represents a percentage proportion of the shared staking pool.

* ##### The composition of the staking pool serves as exclusivity in the resource pool.

* ##### The staking pool is a mechanism that provides fluid and automatic price discovery.

* ##### When a member uses exclusive resources, they release a proportionate amount of TMA in the staking pool to Taupemist.

* ##### Members may increase their staking position for greater exclusivity, and conversely, decrease to withdraw their TMA.

* ##### The number of resources within the Resource Pool should generally exceed any demand, however, this should not have a detrimental effect on Taupemist's portfolio, investment, and trading strategies to which Cole will ensure. To provide security to participants, the Resource Pool will only be available for adjustment once per month and on the first day of any given month. Additionally, any intention to adjustment the resource pool will be broadcasted at first available notice within the Taupemist group Telegram channel.

### Example Scenario
1. Resource Pool: **$1000 BitUSD**
2. John stakes **$20 of TMA**
3. Jane stakes **$20 of TMA**
4. The staking positions of John and Jane mature and the staking pool stands as **50% John; 50% Jane**
5. John activates the Taupemist Gateway service and wishes to convert BitUSD to USD.
6. According to the staking pool, John currently has access to the Resource Pool for a maximum amount of **$500 BitUSD**.
7. John sends **$400 USD** to the Gateway. (**80%** of his available amount)
8. **$16** of John's TMA staking position is released to Taupemist. (**80%** of his staking position)
9. John receives **$400 BitUSD**.
10. The discovered price margin is calculated as follows: **100 / ($400 / $16) = 4%**

[view on GitHub!](https://github.com/TaupeMist/TaupeMist/blob/master/ResourceStaking.md)

[view on Steemit!](https://steemit.com/taupemist/@cmorton/resource-staking-v1-0-0)

**If you have any questions or uncertainties, then please ask via a reply to this post.**

**Thanks!**
