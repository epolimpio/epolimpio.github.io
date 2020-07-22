---
layout: post
title:  "The long-term implications of product decisions"
categories: product
---

"Move fast and break things" once said Mark Zuckenberg. But even at Facebook, this is not a motto anymore - at least not publicly. Is the age of "move fast and break things" is [over](https://hbr.org/2019/01/the-era-of-move-fast-and-break-things-is-over)?

Product managers across the globe still proclaim the virtues of Lean and MVPs as excuses to test the viability of a solution on bare wire. We are irrational beings that underestimate real risks and support our decisions on supposedly rational justification. For instance, early-stage startups typically accept risks because they are in survival mode. And to be honest, in the short-term, most of the risks we accept are relatively low. It is in the medium and long-term that we find the second and third-order effects that are overlooked.

The problem is not the trade-off between moving fast and accepting risks. It is that we are not honest about this trade-off and leave many long-term implications out of the table. Being transparent about those risks can help you make a better decision. Often, going a bit slower today can help you move faster (or avoid stalling) in the future.

Here is a short list I compiled of some of the long-term implications that people overlook. This is not an extensive list and it is based solely on personal experience. I am sure there are many more out there that I need to be aware of.

## Image risks

When I was a risk manager at a wealth management firm this was by far the risk I needed to be most careful. Wealthy people pay for trust when they hire a firm to manage their portfolio. A partner always reminded me: "trust takes years to build but a minute to destroy". A good thought exercise we have often used is the following. Imagine if a reporter had access to all your thought processes, all your files, all the conversations you had even in private to make an investment decision. How would this article come out in the newspaper? This [panopticon](https://en.wikipedia.org/wiki/Panopticon) sort of watching your behavior might sound a bit too much but the thought exercise is really helpful when trying to mitigate image risks.

There are a few tips that also help here, like writing the press release of your product or explaining it to people outside your field who could come with objections that an insider would probably dismiss. In the end, remember that image risks are not about your intention but the external perception of your delivered product. 

## Regulatory risks

Each market operates under a certain set of rules we must comply with. Violating it can really damage the business, if not financially then by jeopardizing its reputation. So it is never too late to build a compliance checklist for your deliverables. Do not allow for gray zones that are not agreed upon with executives and legal.

Make sure you understand the rules of the countries where you operate and which regulations you must comply with. Every market and country is different. From my experience, the best startup point is to write (in case of a new product, using a legal counselor) or read and learn about (in case of a mature product) the terms and conditions and laws that are applicable - the typical set is data protection ([GDPR](https://gdpr-info.eu/)), tax and consumer protection laws.

## Technical debt

Always be aware of what is under the hood of a product. While constructing an MVP it is rather common to compromise technical quality over speed. To run some tests about an uncertain hypothesis it usually pays to accept some shortcuts, but that technical debt should be treated as we move to the rollout.

But there is a caveat here. Polishing the code can really take a lot of time from the team. The Tech Lead and the Product Manager must agree upon what really brings value to the product and to the future productivity of the team. Some technical debt will be left behind - always double-check if it is not something in the critical path or that compromises the value of the product in the foreseeable future.

## Scaling the unscalable

This talks by itself - does the feature scale? Did you run load tests? Did you add monitoring to react to bugs in production? Does your solution have fallbacks? If not, how does the application behave when the system fails?

Running a test on a small sample of users that still did not find the capabilities your new feature provides is completely different than having a robust product in production. But as soon as a test is successful there is a pressure from the business to rollout as quickly as possible and delaying it can cause doubt and frustration from stakeholders.

Always think carefully what are the external forces that will push you to scale faster than possible if your test is an extreme success and mitigate this problem.

## Maintenance over innovation

Too much technical debt and scaling of unscalable and soon you squad will be doomed to firefighting. And innovation and treating the problems root causes will never come back. Before launching a feature beware that your team will own that feature for how long as it lives. Be sure that the time to maintain it will not kill the innovation in time. Look at the portfolio of maintenance your team already has and check if, before your next brand new feature, it is not time for some cleanup and debt payment.

## Get slower

This is really common. You tested something, it worked and went to production. Soon you want to iterate over the solution and figure out that to run a new test over the previous rollout is simply unfeasible - your team needs to almost rewrite the entire solution to run the new test. This is not always avoidable. Flexibility often brings complexity, but whenever possible opt for it - you will need to iterate fast, do not slow down your future self.
