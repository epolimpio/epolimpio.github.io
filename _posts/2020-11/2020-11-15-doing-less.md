---
layout: post
title:  "The wisdom of doing less"
categories: 
    - management
    - product
---

I remember I had this insight after reading the book _"The Goal"_ from Eliyahu Goldratt - "Productivity cannot be measured locally". I had been working with tech products for years and I was quite familiar with lean and agile methods. But I had not thought about the implications of how to measure value and, as a consequence, productivity.

When I had that insight I returned to another book I had read a few years earlier, ["Getting Real"](https://basecamp.com/books/getting-real) from 37signals (now Basecamp). I accessed the online book and re-read the following quote, then fully grasping the concepts underlying the "do-less" thought.

>"Conventional wisdom says that to beat your competitors you need to one-up them. If they have four features, you need five (or 15, or 25). If they’re spending x, you need to spend xx. If they have 20, you need 30.
This sort of one-upping Cold War mentality is a dead-end. It’s an expensive, defensive, and paranoid way of building products. Defensive, paranoid companies can’t think ahead, they can only think behind. They don’t lead, they follow.
If you want to build a company that follows, you might as well put down this book now.
So what to do then? The answer is less. Do less than your competitors to beat them. Solve the simple problems and leave the hairy, difficult, nasty problems to everyone else. Instead of oneupping, try one-downing. Instead of outdoing, try underdoing."

I decided to write this post while reading another book, _"The One Straw Revolution"_ by Masanobu Fukuoka. His way of living and farming resonates with my thoughts on productivity and made me reflect on how we are misled by industrialism on the way we think about it.

### Defining productivity
There are plenty of ways to measure productivity, but it is always a version of the ratio between the value added (or goods produced) to time (or resources or money). For this discussion I will talk about value divided by time as it is most applicable to tech products.

This needs some explanation. Time here is a measure of how much work it takes to add the value. For example, if it takes 10h of code to deliver a feature, it doesn't matter if we can execute it in 5h with two devs, it is still 10h. But it goes beyond that. If there is someone new to the team and they need to spend 20h studying the code before spending that 10h coding, then the time it takes to add value is actually 30h. This is important as the ramp-up of a team in a subject is often neglected. The same goes for the time the team takes in the discovery for a new product or the time a designer spends doing prototypes and usability tests. There is no value without those, so all this time spent should be accounted in the denominator.

And here comes the difficult part: what is value? A feature delivered is not value per se (it can even decrease value). Hours of code is not value. A prototype is not value. And there comes my realisation that value - and hence productivity - cannot be measured locally. To explain that I will refer to an example from the book "The Goal".

The book is actually a novel that tells the story of a plant manager whose plant is suffering from bad results. Headquarters is putting a lot of pressure on him and the whole plant is working extra hours to meet the goals set by HQ. Still, they fail miserably. An insight comes from someone outside the company - I will simplify the narrative here - that they should measure productivity differently. In essence, there is no use in measuring how many parts a division manufactures per day if the assembly of the whole cannot consume all those parts at the same pace. This only produces stock in the middle of the production line, which is expensive and counter-productive. And the story goes on how the plant manager started working on the line to actually improve productivity by "reducing" some of the local productivity. Just like the concept of "just-in-time" advocated by the Toyota production system - produce what you sell, nothing more. Value is the product sold, not parts hanging in a warehouse.

But how does this apply to software development? Well, value is all about identifying what problems your clients have and solving it using technology. Once the problem is (partly) solved and the clients are having a better life because of what was delivered, then you added value. The biggest the impact on your clients (think reach*impact), the bigger the value. There is no value if a problem is not solved for a client. It can even be an internal client. For instance, a team that works in improving the pipeline of CI/CD improves the developer experience and adds a ton of value to a company.

That is all great, but to add more value we do need to work more and deliver more. How is this all related? Think about Pareto or the law of decreasing returns - the more value you add to a product the bigger the effort to add that same value again. And productivity plummets.

### The wisdom of doing less
There is a problem that clients will value a lot. It is surely a tough problem to solve. When you start building (and delivering) the solution, there is always something else to add, another feature, another experience. It seems that as long as you keep asking "what else can we add?" there will be something else to do.

What if instead of asking "what else can we add?" you asked "what else can we remove?". Every problem can be 80-90% solved with 20-30% of the work. When you find the right path, productivity spikes. Less work means shipping faster with less risk. This is the core of agile processes that most people misunderstand. A minimum viable product (MVP) is actually the least product you can deliver that is viable - and viability means that the product is finished, well thought and provides enough value to the customers that they will come back and tell their friends.

Notice that doing less is way harder than doing more. You have to really understand your user. In fact you understand the problem so well that you know the key factors that have impact - those that you must focus relentlessly. This is way harder than intensity and trying errands without actually understanding key effects.

Doing less means prototyping a lot and really tuning the product to what really matters. This involves try and error, of course, but you need to try as much as possible with the least possible effort. That usually means no or little code. It requires a deep understanding of the problems you need to solve and a solid vision on how it is going to be solved. Without this vision as a solid guidance you and your team will probably jump around without much focus - and productivity will go down.

So doing less is the heart of what are the core values of doing product: (i) a deep understanding of the customer; (ii) a solid product vision; (iii) testing quickly with the customers, preferably with no code (using techniques like pretotyping).

When you do less you need less people. Less people means less need for layers of management. You will suffer less with cross communication. People will be motivated by delivering value to customers without feeling guilty by "that feature that was out". The challenge is not to do more than your competitors, but to do less and still be competitive. It is to value your customers needs so much that your focus will be relentless on solving their problems and nothing more.

It will also require less code - only valuable code. Your systems will be cheaper to maintain and the team can focus on adding value to customers. You build slack into the system, spurring self-development and innovation. There will be less bugs, less critical bottlenecks, less side-effects. It will be easier to deploy, cover test case scenarios. It gets way less stressful to deploy.

### Why is it so difficult to put it in practice?
There are two main reasons why I think it is so difficult to put the idea of doing less in practice: (i) it is against our industrialist mindset; (ii) it is more difficult than doing more.

I'll start by the second. Doing more is the easy way of thinking. When you have a difficult problem it is way easier to jump start a solution than actually jump into the unknown of trying to make sense of the problem. Maybe the best solution with your currently knowledge is doing nothing. But we are guided to action, to execution. But doing less doesn't mean you will sit on your chair waiting for ideas to come. It is all about doing the hard job of understanding your customers and their needs, trying different ways of solving the problem and figuring out how to test the effectiveness of the solution without actually deploying any code. And it requires understanding that it requires time and consistency - acknowledging that consistency beats intensity. That value is not about who checks the biggest bucket list, but who builds a short but better bucket list. This leads to our cultural beliefs and why it is difficult to think this way.

Industrialism shaped people to comply and to compete. Schools prepare people for tests, not for blank pages - students are valued by checking as many boxes as they can instead of creating their own boxes. Popular sports make us believe life is a finite game, but in fact life is more like an infinite game. And the best strategy for infinite games is consistency, not intensity. Therefore, doing less is embracing a cultural shift that is hard to implement but in need - now more than ever before.

