# Curve

### Summary

✅ All code is open source

✅ Critical logic requires tokenholder vote to modify

✅ Never critically hacked or exploited

❌ Whales dominate voting

***

### Who do you need to trust?

Curve does a nice job of outlining risks & trust requirements [here](https://www.curve.fi/risks). 

Curve uses smart contracts from other lending protocols on top of its own, so there is often major systemic risk involved. Exploits are more likely to take the form of malicious arbitrage.

***

### **Governance Details**

Curve, like Maker and Compound, also has token voting via CRV. However they have also introduced a token called veCRV, which stands for “vote escrowed CRV”. Basically, if you want to accrue more voting power, you can lock up your CRV for a set amount of time. The longer you lock up your CRV, the more voting power it gains. This is intended to take some power away from whales and give it to smaller, more committed token holders.

Whether or not veCRV reduces or increases trustlessness is a debatable matter. On the one hand, giving smaller token holders a way to accrue more voting power is a good way to decentralize. However, **if whales can turn their already large voting power into exponentially** _**larger**_ **voting power, then it’s probably not serving the goal of trustlessness.** Looking any deeper at veCRV in detail is outside the scope of this post, but it’s something we should consider doing in a future post or video.

Finally, as a strike against trustlessness, **Curve also has an “Emergency DAO”** which consists of just 9 members. The power of this DAO is comparable to Maker’s Emergency Shutdown Module, except the Emergency DAO can stop all activity in the Curve ecosystem _without a token holder vote_. If this happens, CRV & veCRV holders can vote to turn it back on.

Key links:

* [Understanding Curve Voting](https://resources.curve.fi/base-features/understanding-voting)
* [Curve DAO Dashboard](https://dao.curve.fi/dao)

