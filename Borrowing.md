# Borrowing v1.0.1
**Taupemist has the ability to lend BitUSD to members given enough collateral is provided by the member.**

### What is a Borrowing?
This is a lending service that allows Taupemist members the ability to borrow BitUSD through the provision of sufficient TM as collateral.
A minimum collateral ratio will determine the minimum amount of TM collateral that is required for a given amount of BitUSD.
Over time the TM portfolio price will fluctuate, meaning that the value of the collateral and therefore the collateral ratio will fluctuate. **If the minimum collateral ratio is reached then the borrow position will be automatically closed meaning that the member will keep the borrowed BitUSD and collateral will be forfeited and absorbed into Taupemist's reserves**.

Members should ensure that the collateral ratio is safely over the minimum collateral ratio to minimise the risk of automatic closure.
In short, the higher the amount of collateral and the lower the amount of BitUSD borrowed, the higher the collateral ratio and the lesser the degree of risk to the member.
If the TM price increases, the collateral ratio will increase and similarly if the TM price decreases then the collateral ratio will decrease.
The safest occasion to borrow will be when the TM price displays a consist uptrend and/or the borrower has plentiful TM to provide as collateral.

This is a powerful service and adds a useful alternative to members that are considering to sell or power-down TM due to a short-term desire or requirement for cash or crypto. Furthermore, this allows members the ability to bet on the future price of TM.

The BitUSD to be used in this service is contained within Taupemist's investment portfolio and belongs to the Taupemist organisation. It is essential that the current investment objectives and other services are maintained and this service does not operate in detriment to the organisation and it is for that reason, that the availability of assets to this service will be sparsely and transparently adjusted over time.

As Taupemist is a non-profit organisation, members are not required to pay any fee or profit margin for the user of this service.
BitUSD quantities will be measured in chunks, where a chunk will represent a fixed amount of that asset.
Therefore, a member will request their desired amount per number of chunks, opposed to the amount in dollars.

### How does it work?
Taupemist members that hold the required level of membership and desire to borrow BitUSD should first check the availability of chunks in the comment thread. If chunks are available then they can make a borrow request. Borrow requests should be posted in the comment thread of this Steem article to be legitimised and posted in the Telegram channel to advertise the request to the organisation.

The request will receive a response within 24 hours, which will be an approval if sufficient chunks are available and the member holds sufficient TM. The current minimum amount of collateral will also be specified.
On approval, the member should transfer their desired amount of collateral to Taupemist and when received, Taupemist will transfer the requested BitUSD amount to the member at which point, the borrow position will become active.

Taupemist will hold the collateral in escrow meaning that it still belongs to the member, however, **the collateral will be locked and Taupemist will not have the permission to use the amount for any purpose**.

The borrower has the ability to increase the collateral ratio at any time they wish. This can be achieved in two ways. The amount of collateral can be increased through the further submission of TM.
Secondly, the amount of BitUSD borrowed can be decreased by returning an amount of the BitUSD the was lent.
A borrower also has the ability to withdraw TM from the collateral which will decrease the collateral ratio.

There is no time limit and all borrow positions will remain open until either automatically closed or the full amount of BitUSD lent is repaid to Taupemist.
On full repayment, the remaining collateral will be returned to the member.

### How much BitUSD does 1 chunk contain?
**One chunk** will always be equal to **$100 BitUSD**.

### How do I know if chunks are available?
The chunks available will be advertised and logged historically through the comment thread of this Steem article.
Please check back here for availability.

A notification will be announced to Taupemist members inside the Telegram channel when Taupemist updates the chunk availability.
**Taupemist's chunk availability updates have a cooldown of one month meaning that at least one month must elapse between these updates**

### What is the minimum collateral ratio?
The minimum collateral ratio or call price is **1.75:1** of **TM:BitUSD**.

### How should I decide how much I can borrow and the amount of collateral to provide?

As a borrower, you will need to determine the following values:
1. BA: the amount you wish to borrow (BitUSD)
2. MTP: the minimum TM price where the position would close (BitUSD)

How do I do this?
1. Consider the amount of BitUSD that you wish to borrow to **determine the BA**.
3. **Take the MCR** specified in this document.
2. Review the TM price history to **determine your MTP** (lower MTP = higher security).
2. Use the following formula to **calculate the collateral amount (TM)** that you should provide: **BA * MCR / MTP**

### What does a borrow request look like?
Here's an example borrow request to borrow 1 chunks of BitUSD.
```
BORROW REQUEST
CHUNKS: 1
```
Assuming that the request is approved and if in this example, the minimum collateral ratio is **1.75:1** and the current TM portfolio price is **$100** then the minimum amount of collateral would equal **1.75TM**.
Therefore, the member may wish to provide **3TM** which would equal a collateral ratio of **3:1** and provide the member with security in the case that the TM price decreases.

### I've been approved to borrow 1 chunk of bitUSD, what are the following steps?
1. Log in to your BitShares account and pay the collateral amount to the taupemist1 account.
2. Taupemist will transfer your requested amount of bitUSD to your BitShares account within 24 hours.

### The collateral ratio is low/close to the minimum, what should I do!?
You have three options at your disposal.
1. Increase the amount of TM in collateral.
2. Repay an amount of BitUSD lent.
3. Allow the collateral ratio to reach the minimum which will close your borrow position.

[view on GitHub!](https://github.com/TaupeMist/TaupeMist/blob/master/Borrowing.md)

[view on Steemit!](https://steemit.com/taupemist/@cmorton/borrowing-v1-0-0)

**If you have any questions or uncertainties, then please ask via a reply to this post.**

**Thanks!**
