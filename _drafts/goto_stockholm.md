---
layout: post
title: GOTO; Stockholm  
---

# {{ page.title }}

*XX May 2016 - Stockholm, Sweden*

### It's not just Micro Services, [Fred George](https://twitter.com/fgeorge52)
Coming back to "full stack developers" (trying to get away from since the 70s) - maybe its good to have these ppl who can do everything?

"80% of the time you do not know the problem you're working with"

"If youre still doing iterations 2-3 weeks, and you did that 2-3 years ago, you're not agile anymore. You need to push the envelope!"

* Dont be afraid to use "Valley Tech"
	Cloud exploatation
	New programming languages
	Open source (use, contriubte)
	Continouse releases
	Specialized databases

* Hardware ("new machines") leadtimes
	1990 - 1-1.5 year to get a new machine in place
	2000 - VMs, in a week or so
	2010 - Commercial cloud, 5-10 minutes
	2015 - Doker, 5 seconds

	No more capacity planning, no need for dedicated ops team(!)

* Service impact
	More and more services, less and less lines of codes per service


* Event bus
	No more databases?
	kafka, zero mq (0mq checks all messages on eventbus kafka, and gets to correct services, which in turn responds to eventbus)

* Incremental applications

case study mailyonline render first page -> lesson: change language when calls for it, use modern techs that solves the rpoblem better
	130k loc java/jsp
	4k loc clojure

"Whats the difference between an expert architecht and a car salesman -> the car salesman knows that he's lying"


Try to come back to the 70s, where the client tell you about their problem, and you write code for it

### How Platforms Work, [Casey West](https://twitter.com/caseywest)

MVP, spending a lot of time on "minimum", lot less on "viable".

If you have to manually conf like dynamic dns, routing, load balancing, you're not very automated -- the automation should be there already

bosh.io

cloundfront.io
cloudfoundry.org

"If you're in a meeting and someone says 'lets build this enterprise app' you say 'ok! i'll add Analytics'"


Cycle credentials evey now and then in production.

You REALLY need continuous deployment/delivery for running microservices
















### Further reading
* [GOTO; Stockholm](https://gotosthlm.com/)
