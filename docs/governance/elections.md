---
layout: default
title: Elections
parent: Governance
nav_order: 1
has_children: true
permalink: docs/governance/elections
---

{: .fs-26 .fw-100 }
# Elections

The core governance of Socket Network is based on elections. Hence, the Election plays an important role here.  All important decisions inside any shared community are based on elections in this app. The preferences inferred through Surveys may be pushed to elections for final implementation or rejection. 
{: .note }

Each election is always associated with a role. Roles are tied to access on chain.	 
For example, MAyor role in a city or the creator of a community in that Community. 

Each Election is a chain. Eligibility of voters is determined by subscriptions. Eligibility can be deligated to someone else. OR Sortition can be random users (like a jjury) who are compensated. Each ballot will have an owner and a deligate field. If the owner deligates then the deligated user can vote on their behalf. Who voted has to be recorded.			

## Types of Elections

### Simple Elections : 

Here the election is triggered by the creator/who has requested for a transaction from treasury, for a modification of community name or for installation of an App inside that shared community.  Each person owning the community token gets a chance to cast his vote on the subject/request/issue and the absolute majority wins the election and the decission is made according to the favours of the majorily. 

**Use Case:** Change of name of the community which is put to simple vote amongst the members of the community and if the majority of the member voters favour for the change of the community name, then it will be done accordingly.

### Conviction Elections

This type of election is required to decide on one or more decisions to be made from many proposals. Each voter will be given 100 points (this number is given for easy understanding) and the voter distributes the given 100 points amonst the proposals accoding to his priority. Finally each proposal's acquired priority points are cumulated and listed from the highest points earned to lowest earned points. This makes it easier for the community to go with one or more proposals starting from the highest points earned proposal.

The longer you hold a preference for a certain proposal, the more that proposal gets your conviction. Your conviction grows according to a half life decay curve, giving more weight to that preference over time, up to a certain limit. If you decide to switch your preference to a new proposal, your conviction drains out of the previous proposal against the new proposal which you support. 
{: .note }

**Use Case:** 

### Cumulative Elections

This type of election is necessary to decide on multiple issues at at time. Each member gets more than one vote and each vote will carry a equal fraction of points. The voter has a liberty to choose and support only one single person / issue / or proposal and vote all his given votes on the same person/issue/proposal. Finally, all the votes are calculated and multiplied by the fraction value (face value) of each vote to arrive at the final decision. 

**Use Case:**

If there is election for 4 council members and there are 6 contestants, then each voter gets 4 votes and each vote has a face value of 1/4 points. The voter can opt to put all the votes on only one person or one or more persons, maximum being one vote for each person of his choice. Finally, the votes earned by each candidate is cumulated and divied by 1/4 to get his position in the winning scale. The top highest 4 candidates are declared as the winners and elected to be the council members for the said term. 

### Quadratic Elections

The Quadratic voting requires more complex calculations than the regular rank choice voting. With the right interface, it is an intuitive and simple-to-use but a profound mechanism. 

**Advantages**

Weighting votes quadratically can be advantageous in protecticn minority advocates, Balancing power, and/or Capturing community sentiments. 

**Protecting minority advocates**

Quadratic voting helps in addressing issues where there may be an opinionated and passionate minority whose interests are ignored by an indifferent majority. Quadratic votine allows minority interests to be recognised and better balanced.

**Balancing power**

Quadratic voting helps in balancing power among the communities through a large spread in voting power. Compared to simple voting, the Quadratic voting can be better in recognizing the outsized voting power of tycoons, while balancing their weight in ways that can feel more democratic. The Quadratic voting can better recognize stakeholders that are more active or invested.

**Capturing community sentiment**

In using the simple voting on elections with several choices, sometimes the results may appear close to each other, but there may be significant differences in understanding and convicting to the choices. The Quadratic voting weighs the voter's passion and helps in giving a more accurate result based on the community sentiment.


**Use Case:** 

In a multi choice election (more than two options), each voter is given a budget of 100 “credits”. Each voter allocates the credits among all available options as per his/her choices. The 100 credits could all go towards one option, or the credits could also be split among all choices and weighted based on the preferences.

The counted votes are the square root of the “credits” allocated to each choice. 

   **cost to the voter = (number of votes)2.**

This means that 100 credits applied to one choice are 10 votes. 25 credits applied to one choice are 5 votes. 4 credits applied to a choice are 2 votes, and so on as shown in the table below.



### Vote pricing example

| Number of votes      |  "Credits" applied | 
|--------------------- |--------------------|
|         1            |          1         | 
|         2            |          4         | 
|         3            |          9         | 
|         4            |         16         |
|         5            |         25         | 
|         6            |         36         | 
|         7            |         49         | 
|         8            |         64         |
|         9            |         81         | 
|        10            |        100         |








