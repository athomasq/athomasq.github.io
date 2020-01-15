---
layout: post
title: APIs Are Eating the World
thread: https://twitter.com/athomasq/status/1217269852014096385
---

*Visa is [buying Plaid](https://techcrunch.com/2020/01/13/visa-is-acquiring-plaid-for-5-3-billion-2x-its-final-private-valuation/) for $5.3 billion.  The [hottest startup in Silicon Valley](https://stripe.com/) is an API company.  Accel recently hosted a [conference](https://techcrunch.com/2019/09/06/apis-are-the-next-big-saas-wave/) devoted solely to API firms.  What's going on?*

----

<br/>

### The API-First Business

One of the most influential strategic moves in tech history was Jeff Bezos' API memo at Amazon.  Bezos wrote: 

- All teams will henceforth expose their data and functionality through service interfaces.
- Teams must communicate with each other through these interfaces.
- There will be no other form of inter-process communication allowed.
- It doesn’t matter what technology you use.
- All service interfaces must be designed to be externalize-able. 
- Anyone who doesn’t do this will be fired. 

This move had two dramatic consequences for Amazon.  First, and most obviously, it laid the foundation for what would eventually become Amazon's largest, fastest growing and most profitable business segment, Amazon Web Services (AWS).  

More subtly, it created an internal communication mechanism by which Amazon could retain the nimbleness of small (two-pizza) teams while scaling to dozens of business lines and a trillion dollars in market cap: the ultimate modular company.

But it was also prescient.  The "service interfaces" at Amazon became the blueprint for dozens of tools, processes and entire companies over the next couple of decades, and their story is just beginning.

<br/>

### APIs Are How Software Talks

*Software is eating the world.*  In the decade since Marc Andreessen wrote those words, we've seen ever more businesses being transformed by software.  

These changes have mostly fallen into two categories.  There are companies that use software to function better, with tools like Workday for HR, or Zoom for conferencing, or Slack for messaging.  And then there are companies that use software to execute their business models, like Airbnb and Shopify.  

Both of these categories tend to be **internal** -- software improves inefficient (non-software) processes, or drives core business applications.  But a huge part of what companies do is **external**:  communicating with customers and with other companies; transactions, invoicing and payments; exchanging data and tasks; supply chain and logistics; and more.

This is where APIs come in.  APIs are how software talks to other software.  

*As companies become more software-centric, APIs will increasingly be the channel over which they communicate.*

<br/>

### The Plaid Paradigm

Plaid is a great example of this paradigm in action.  

Plaid is a channel for fintech startups (and ultimately, retail customers) to talk to banks and bank accounts.  The Plaid API is eating the physical bank branch: it replaces bank tellers and request forms and check deposit slips and ATMs and customer support phone lines and dozens of other in-person interactions with software calls.

In this setup, fintech apps are the user interface, offering all sorts of behaviour and functionality (track your spending!  save automatically!  trade stocks!), while banks are the underlying database, actually storing and moving the money.  And Plaid is the glue connecting these layers.

This is powerful, because (early to mid-stage) fintechs don't necessarily want to be banks, while banks aren't necessarily good at offering the products and services that customers want.  Plaid allows each side to focus on what they're good at, while embedding themselves into the heart of each interaction.  I'd say Visa got a bargain with their acquisition.

<br/>

### APIs Everywhere

Uber may have started out as a taxi substitute, but the company is increasingly positioning itself as an "API for transport".  By adding new types of mobility, buying stakes in other ride-hailing firms, and releasing new apps like Eats and Freight, Uber is working towards a future where if you want to move item X from point A to point B, you simply make an API call, and the Uber ecosystem does the rest.  Uber's API will have eaten the entire user-facing transportation industry.

You can see similar patterns emerging in every vertical.  Stripe is an API for online payments.  Quandl is an API for financial data.  Flexport is an API for international trade.  

In each case, businesses (software firms, investment managers, importers) interact with other businesses (customers, data vendors, exporters) via API instead of via older and less efficient methods (invoices, terminals, freight forwarders).  **APIs are eating the (B2B) world.**

There are even meta-API companies emerging!  Zapier and Airflow help chain APIs together.  Postman and Kong help developers use APIs more effectively.  (A previous generation included Apigee and Mulesoft).  A big part of Slack's appeal is the way its webhooks make APIs accessible to humans.  

<br/>

### Just Getting Started 

To ask the classic VC question, how big can this get?  This slide from Accel shows the progress API-first companies made between 2015 and 2019:

<img src="/assets/img/api-companies-accel.png" alt="API Companies" class="image">

The experience of SaaS suggests we still have a long way to go:

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Salesforce customers today:<br><br>24 pay $20M+ per year<br>100 pay $10M+ per year<br>1,600 pay $1M+ per year<br><br>Enterprise software markets are turning out to be a lot larger than most expected.</p>&mdash; Chetan Puttagunta (@chetanp) <a href="https://twitter.com/chetanp/status/1217146989370052608?ref_src=twsrc%5Etfw">January 14, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

One thing does seem certain to me, and that is that Plaid will not be the last high-profile API acquisition!
