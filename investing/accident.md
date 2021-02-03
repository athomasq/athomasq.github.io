---
layout: essay
permalink: /:basename/
title: The Accidental Trader
date: 2020-09-07
---

*This is 100% not career advice.*

----

<br/>

I fell into finance by accident.  Growing up, I wanted to be a scientist -- either astrophysics, or biotech -- Carl Sagan or Jurassic Park.

This in itself was an unusual option for an upper-middle-class kid in 1990s India.  Engineering, medicine, law, accountancy -- these were the "safe" choices, and that was my family: my father was a doctor, my mother taught high-school English, I had 3 uncles who were engineers and 3 others who were lawyers.  

And that might have been me.  I was accepted into India's top medical school, and also into India's top engineering school.  (I've always been good at competitive exams).  But I took the path somewhat less trodden; I joined IIT Bombay, but instead of mechanical or electrical or chemical or civil engineering, I chose to major in physics.  A career in academia beckoned.

I was in for a rude awakening.  I quickly realized that there was a world of difference between *liking* physics as a subject, and *doing* physics as a career.  I simply didn't have the singlemindedness (some would call it tunnel vision) required to be a successful academic.  I also lacked the patience to complete a 5- to 7-year PhD followed by multiple post-docs before eventually landing a tenure-track job.  To this day, quantum mechanics, classical mechanics and statistical mechanics remain some of the most beautiful intellectual constructs I have ever come across, but a physics career was not for me.

<!-- Instead, I threw myself into extracurricular activities. I stood for election as the leader of IIT Bombay's student body, and won. I was on the core group for Mood Indigo, helped launch the first TechFest, and set up India's first campus internet.  I won a bunch of prizes for everything from quizzing to debate to writing to dramatics: intramural, rep and all the way to national level.  All in all, I had a whale of a time.-->

<!-- Disillusioned with academics, I threw myself into extracurricular activities and student leadership. I was institute general secretary, on the core group for [Mood Indigo](https://en.wikipedia.org/wiki/Mood_Indigo_(festival)), helped launch the first [TechFest](https://en.wikipedia.org/wiki/Techfest), and set up India's first campus internet.  I also won a bunch of awards and competitions. -->

So when it came time to graduate, I found myself at a loose end.  While my classmates were winning full-ride grad scholarships to Caltech and Stanford and Princeton and Yale and Cornell, I entered my senior year completely at a loss for what to do next.  I was accepted into IIM Ahmedabad, then as now India's top business school (there's that competitive exam thing again), but I didn't really want to go there;  I wanted to leave the cloister and experience the real world.  At the same time, the types of entry-level positions available to newly minted engineers -- management tracks at large Indian corporates, software development for offshore IT firms -- didn't seem terribly appealing.

And that's when serendipity struck.  I was offered a strange job via a strange set of circumstances.  The company making the offer was called Simplex Capital, they were 6 people (I would be the 7th), and they were setting up a "hedge fund" with a small pool of money.  They were based in Tokyo -- !!!! -- but one of their principals had family in Bombay, was connected to me, and offered me a rather vague role as a "quant odd jobs person".  


----


Now you have to remember that this was the mid 1990s.  At the time, hedge funds were still a rather obscure corner of finance; they had none of the glamour (or notoriety) they have today.  Quantitative investing was in its infancy; firms like Citadel, D E Shaw, Millennium and AQR were just a few years old, while others like Winton and Two Sigma hadn't yet been launched.  Most people didn't know a hedge fund from a hedgehog.  

It was doubly tricky given that I was in India.  The country was just emerging from 40 years of soft socialism.  Markets were either moribund or corrupt; people who worked with money were looked at with either suspicion or disdain.  The best universities in India produced excellent undergraduates, but unlike the Ivies or Oxbridge, there was no pipeline linking them to the analyst-associate-VP-MD path on Wall Street.

Not helping matters was the fact that I was utterly clueless about finance.  I didn't know the difference between a stock and a bond; I had only the faintest grasp of macroeconomics; and I confess that I too looked upon the business of money with a mixture of suspicion and disdain.

On the other hand -- Simplex sounded so cool!  They explained their business as  "building mathematical models of the market, and then profiting if those models were correct".  To me that was the future, right there.  No more guesswork, no more hand-waving, no more investing based on "trader's instinct" and "gut feeling".  I had visions of Kepler, Newton and Tycho Brahe using data and mathematics to build the edifice of classical celestial mechanics, and wanted to do the same for market dynamics.  

My friends thought I was nuts.  To reject higher studies in the USA, to reject IIM Ahmedabad with its promise of job offers from McKinsey or Bain, to reject managerial careers at blue-chip Indian companies, all in order to join a tiny little firm that nobody had heard of, in an industry that nobody knew anything about, in a country I'd never been -- it was contrarian to the point of insanity.  

But to me, all those bugs were features!  New horizons!  It was an adventure.  I'd learn fresh skills, speak a foreign language, explore a different (and to me, fascinating and exotic) country and culture.  What's the worst that could happen?  Simplex could fire me, or I'd quit -- no big deal; I'd come back to India, having enjoyed a paid vacation in Japan, and hit the reset button: re-apply to business school, re-take the admission tests, and breeze through.  (I later realized how arrogant and privileged this was).  Meanwhile, in the best case the upside was unlimited.

My family was somewhat bemused, but entirely supportive.  So in August of 1998, knowing no Japanese and knowing nothing about finance and barely knowing how to code, I hopped on a plane to Tokyo to take up a new job programming financial models for a Japanese hedge fund. 

----

I loved it.  

I started out as a true quant odd jobs person -- everything from data entry (manually transcribing bond prices into our database) to printing daily reports to fetching coffee and lunch for the traders.

Eventually I started doing some actual work: coding our basic analytical infrastructure.  The firm was so young and so small, it was all green fields.  Me and one other programmer -- fun fact: 15 years later we became co-founders at Quandl! -- wrote everything from scratch.

This was -- and I cannot emphasize this enough -- the best possible education in finance for me: better than any amount of solving stochastic equations.  To this day I remember creating a C++ object called  **cashflow** -- an ordered pair of date and dollars.  Bonds were just vectors of cashflows.  Derivatives were cashflows with conditions attached.  And so on.  Once you start thinking of (and coding the behaviour of) financial assets as streams of cashflows, everything else -- discounting, optionality, correlations, distributions, convexity -- becomes a lot easier. 

Even better, the exercise of programming this infrastructure, and then matching the results with real-world data, gave me a keen appreciation for all the wrinkles of modern finance: settlement and delivery rules, day-count conventions and calendar effects, quote formats and much more.  The devil is always in the details.  

I then moved from baseline infrastructure to the fun stuff: predictive modelling.  In this field, Simplex was small but mighty: our founding partner had been part of John Meriwether's famous bond arbitrage team at Salomon Brothers, and we had plenty of additional horsepower.  The quants designed -- and I coded, calibrated, backtested and deployed -- models for yield curves, options, futures and much else.  Many of these instruments were still woefully misunderstood (and hence mispriced) by the market, so there was easy money to be made from arbitrage.

I worked hard.  Japanese work culture is pretty intense, and so is Wall Street work culture.  The intersection of the two ... well.  I lived and breathed markets.  It was some of the most fun I've ever had: work that is sufficiently intellectually stimulating can feel like it's not work at all.  I had two mentors -- one in technology and one in trading -- who taught me immense amounts, and I was a keen student.  

As time went by, I found myself doing more and more "front-office" tasks.  I went from coding other people's models, to creating my own models, to building and testing strategies using those models, to placing small trades, to placing large trades, to managing a full-fledged portfolio.  One day I woke up and realized I hadn't written any code in months; I was a full-time trader.  

-- 

I discovered I was really good at it.  

I was mathematically inclined, fast at processing (large quantities of) information, and had an excellent memory.  Perhaps it was my childhood experience with war and invasion; perhaps it was the fact that I never planned for (or even particularly wanted) a career in finance; perhaps it was just my personality type -- for whatever reason, I found that I had an unusually high tolerance for risk and uncertainty, even compared to other traders.  Volatility and incomplete information didn't bother me.  I trusted my own judgement and had a naturally contrarian streak, but I wasn't shy about updating my priors or admitting I was wrong ("strong opinions weakly held").  Best of all, I played to win, not to "not lose".  

<!--
The key word here is "played".  I always treated trading as a game, not as real life.  Certainly the sums involved were unreal.  At one point I was short over a billion dollars (10% of the issued notional, a much larger percentage of the actual tradeable float) of a single 30-year government bond: every 0.01% change in its yield would cause a nearly $2 million swing in my P&L.  Not small potatoes! 
-->

Over nearly a decade at Simplex, I rose from junior trader to senior trader to portfolio manager to head of global (ex Japan) trading.  I started out in fixed income arbitrage, then branched out into long-short relative value and global macro.  At one point the most interesting trading opportunities were in the US Treasury market -- the most liquid, most eyeballed market in the world, and ground zero for a great many quant strategies.  So I set up a US office for Simplex and moved there to lead a small team.  We did well, and I grew ever more confident; if you can make money trading Treasuries, you can do it anywhere.  

Markets never stay still; the models I began coding in the late 1990s were already hitting obsolescence by the early 2000s.  In response, we built one of the industry's first "high-frequency trading" systems for Treasuries.  Our tech was able to capture yield curve arbitrages smaller than a basis point, with a response time of less than second.  By modern standards this seems laughably inaccurate and slow, but back then it was state of the art.  Over the next few years I saw electronic trading go from 15% of the bond market to 85%.  Change happens slowly, and then all at once.


--

It was a good run.  It was a *great* run.  And then -- I quit.  Boredom, circumstance, new perspectives, changing priorities, family considerations, and macro conditions all played their part.  I had fallen into finance by accident, and just like that, I decided to fall out of it.  In the weeks leading up to my 30th birthday, I exited all my positions, wound down my portfolio, and walked away.  

But that's a story for another day... 


