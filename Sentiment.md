# Sentiment v1.0.1

**Governance is fundamentally essential for any organisation to operate effectively and starting now, the Taupemist organisation will implement the first service to allow a rudimentary form of governance and decision making to the organisation!**

### What is the Sentiment service?
The Sentiment service will allow members to submit surveys in order to gauge the sentiment or public opinion of the Taupemist organisation towards an idea, proposal or question.

Members will respond to these surveys through the submission of TMS (Sentiment) and each member who holds TM possesses TMS at the following ratio: **TM:TMS Ratio: 1:10**

Unless a survey explicitly specifies a duration, the default duration will be used: **Default Duration: 1 week**

### How does it work?
Taupemist members that hold the appropriate level of membership can create, submit surveys and respond to them.
At the end of a survey, all response values and their weight will be collected and the central tendency will determine the result of the survey.

### What Survey types exist?
- __boolean__: is used for questions. Submission value can be true or false
- __(USD/TM) range__: is used to discover an amount. USD or TM range type must be defined.
- __compensation__: is used to discover an amount to be paid to a member as compensation. Range type is USD and compensation will be paid in TM.

### How do I submit a survey?
##### A Survey is composed of three fields.
The __title__ is the title or name of the survey.
The __type__ is the survey type.
The __duration__ is an **optional** field to state the duration of the survey.

A member can submit a survey in this format as a post on the steem blockchain using their desired steem website (i.e. [steemit.com](https://www.steemit.com)) and the tag: taupemist.

### How do I submit TMS to a survey?
##### A TMS Submission is composed of three fields.
The __value__ is the answer or result that the member supports depending on the survey type.
The __weight__ is the number of TMS allocated towards this submission.
The __reason__ is an **optional** field that can contain some arbitrary information either required by a specific survey and/or to support that member's chosen value.

A member can submit TMS in this format as a response to a survey post on the steem blockchain using their desired steem website (i.e. [steemit.com](https://www.steemit.com)).

### Can I submit TMS to multiple surveys?
Yes! If for example, a member currently has for 50TMS, then that member has the ability to submit at maximum, 50TMS per each survey.

### Can I submit multiple values to the same survey?
Yes. If for example, a member has 100TMS, then a member may wish to submit 50TMS towards one value and 50TMS towards another.
If a member submits more TMS than they have available, then the maximum amount will be assumed and the most recent submissions will take priority.

### Can I change the amount of TMS in a submission?
Yes. A member can post a new TMS submission with the same value as the former, and specify a new weight. At the end of the survey, the most recent weight for each value will be used.

### Am I required to participate?
No, members are not required to participate and does stand to lose anything other than a degree of influence over Taupemist's decision making.

### What does a Boolean Survey (Question) look like?
```
SURVEY
Title: Does Taupemist need a new logo design?
Type: boolean
```
```
SURVEY SUBMISSION
Title: Does Taupemist need a new logo design?
Value: true
Weight: 100TMS
```

### What does a Payment Survey look like?
```
SURVEY
Title: How valuable is a new logo design to Taupemist?
Type: usd range
```
```
SURVEY SUBMISSION
Title: How valuable is a new logo design to Taupemist?
Value: $200
Weight: 100TMS
Reason: a quote from New Logo Ltd stated $200
```

### What does a Compensation Survey look like?
```
SURVEY
Title: Bitshares Account Setup
Type: compensation
```
```
SURVEY SUBMISSION
Title: Bitshares Account Setup
Value: $250
Weight: 100TMS
Reason: The TM asset will be invaluable to the growth and operation of the organisation
```

[view on GitHub!](https://github.com/TaupeMist/TaupeMist/blob/master/Sentiment.md)

**If you have any questions or uncertainties, then please contact me via the Official Taupemist Group**

**Thanks!**
