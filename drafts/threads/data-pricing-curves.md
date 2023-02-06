---
layout: thread
permalink: /:basename/
title: Data Pricing Curves
threadurl: https://twitter.com/athomasq/status/1305945633661091840
date: 2020-09-15
---

<br/>
<br/>

**Pricing curves for data** are dramatically different from pricing curves for software, hardware, services, or consumer products.  Here are some of the things I've learned across 100s of data products and 1000s of enterprise data sales.

Price per data point first increases, then decreases with **quantity**.  Small datasets are usually worth less than big ones.  But beyond a certain point, adding more data points doesn't add **marginal information**, and hence the price plateaus.

Exception: some datasets are **all-or-nothing**.  For example, if I'm doing index research, a dataset covering 499 of the stocks in the S&P 500 is useless to me.  Depending on the application, there may be a **minimal viable corpus** (h/t Martin Casado for the phrase).

Price first decreases, then increases with **adoption**.  As datasets become commoditized, prices decline, but once a dataset becomes **table stakes**, its price goes up again -- especially if there's a single dominant supplier.

Data is meaningless except insofar as it generates **insight**.  And potential insights and their applications vary enormously from user to user.  A dataset that's invaluable to one may be worthless to another.  

Price is typically an increasing function of **context**.  Most datasets have limited standalone utility; the more context a user puts around it, the more value.

Rough analogy: neither weight alone, nor height alone, are very useful in evaluating health.  But both together can be.  And the more **dimensions** you add (age, gender, history, diet, exercise), the more the insight you can draw from individual fields.

But context can detract from value too.  **Marginal impact** is what matters.  To continue the analogy above, if you already know weight, height, age, gender and history, the marginal impact of waist-to-hip ratio is minimal.  If you know none of those, then WHR is very valuable.

Rigorous datasets with **clear takeaways** command a deserved price premium.  Somewhat counterintuitively, less rigorous datasets with ambiguous interpretations have lower customer churn rates -- because they're "never wrong".

Rigor, in this case, is not a function solely of the data; it depends on the application as well.  In general, the more **predictable** a company's returns are, the better they will be able to impute value to data that can boost those returns.

Airline yield management, rideshare pricing, ecommerce acquisition funnels, and quantitative investing are all examples of highly-predictable business models.  Turn dial X, and observe result Y.  This makes it easy to measure the marginal impact of data on returns.  

Unlike customer acquisition, the cost of data acquisition does not decrease with **scale**.  In fact, because so much data is in the long (and messy) tail, marginal costs often increase.  

Unfortunately, this runs counter to marginal data value, which declines with scale.  Successful data businesses are those where the **value and cost curves intersect** at an economically viable point.  Often, they don't.

Data appears to have asymptotically zero marginal **ongoing cost** (for storage, replication, delivery), but this is a misconception. Obsolescence, maintenance and customization all impose recurring costs for both vendors and customers.

Data becomes **obsolete** way faster than hardware or even software.  Nobody wants to make decisions based on stale data. 

Nor do they want to make decisions based on incorrect data, and errors are everywhere.  Data **quality control** is still in its infancy as a practice, and correspondingly expensive if you want to do it right.

Raw data rarely drives value; it requires work.  Whether it's the data consumer paying for this work, or the data producer, doesn't matter: the **cost of value extraction** is not zero.  What's more, this work tends to be custom, imposing limits on scale and reusability.

Every customer is different, and every use case is different.  Only a handful of datasets are both universal in application, and ubiquitous in adoption.  These are the ones that become **table stakes**.

Given limited resources, there's often a **tradeoff** between quantity (lots of messy data) and quality (a small amount of clean data).  The key is finding a sweet spot where there's enough of both to generate business value.

You would think that being digital, data is **non-rival**, but that's not true.  Some datasets explicitly gain their value from having only one user; think of alpha generation in financial markets. 

**Training data** has different economics from production data.  Training data has large one-off costs but also retains its value over time.  

Thanks to the rapidity with which ML techniques advance and disseminate, high-quality training data can be every bit as valuable as unique financial data, for a similar reason: it's a source of sustainable advantage.

Truly unique, valuable, **proprietary datasets** lend themselves to wholesale transfer pricing, allowing their owners to capture much of the value accruing to the end user.

All the above points apply fairly obviously to external data assets that a company acquires or purchases or ingests.  But they also apply to **internal data assets**, and most companies don't analyze internal data through these lenses.

**Price discovery** plays a big role in all of this.  Sometimes, the market doesn't clear; the cost of producing data is higher than the price that consumers are willing to pay.  

Especially for "new" datasets, this bid-ask spread is exacerbated by **uncertainty** on both sides regarding the true value of the data.

This creates advantages for incumbents with data **scale effects** (ideally, where data begets data) -- the less liquid the external market for a dataset, the more valuable their internal data becomes.  

It also creates opportunities for intermediaries.  By making raw data assets easier to consume, these intermediaries decrease **total cost of adoption** for end-users.  This in turn helps the market clear where previously it might not have.

Data illiquidity is also behind the adoption of **non-monetary data exchange** models -- most commonly, give-to-get and data cooperatives.

Data **network effects** are rare.  In most cases, costs go up and marginal insight goes down with scale -- the exact opposite of what you would like to see.  For this reason, data is unlikely to be a viable moat.

But sub-scale advantages may exist.  That's why it's vitally important to understand the actual cost and insight and coverage curves that govern how your data **interacts** with your business model.

The economics of data companies depend on the economics of the underlying data.  And increasingly, every company is now a data company: either a producer, or a consumer, or a transactor, or usually, all of these at once.
