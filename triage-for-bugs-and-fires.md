# Triage for Bugs and Fires

> "A bug triage reviews bugs and decides whether and when to fix them. The decision is based on the bug's priority, and factors such as project schedules." - [Wikipedia](https://en.wikipedia.org/wiki/Software_bug#Bug_management)

Bug and fires will happen occasionally and sometimes often. All bugs eventually need to be fixed and all fires eventually need to be put out. A corollary to this is that _not_ all bugs need to be fixed immediately and _not_ all fires need to be put out immediately.

This triage process helps us reduce the amount of disruption to our planned work \(i.e. new features, enhancements, upgrades\) by the inevitable emergence of unplanned work \(i.e bugs and fires\).

Prioritization is the most important aspect of this process. We should _always_ be considering whether the work we're doing at the moment is more or less important than the bugs and fires that appear at any given moment.

## The Triage Process

The process begins when the engineering team becomes aware of a bug or fire via monitoring, user feedback, support team or other some other indicator.

The process proceeds from informal to formal, as many bugs and fires can be resolved with a quick discussion that doesn't necessarily disrupt ongoing work. In fact, this discussion step can reduce the amount of overall time spent on bugs and fires by short-circuiting process to get straight to a solution.

As with most processes, there is always going to be ambiguity. This document is meant to provide guidance, though precisely when and how to use this process is left to the judgement of each individual engineer. 

![The IFTTT Triage Process](.gitbook/assets/triage-process.png)

## Discuss

The first step in triage is to facilitate a discussion to determine the size, severity and impact of and issue. This discussion should include all key stakeholders and knowledgeable parties.

Very often, a resolution can be at this point and nothing else needs to be done other than to fix the issue and move on. Although, you should always be aware of common or trending issues that might indicate a larger underlying problem.

If a quick and immediate resolution cannot be found, the issue needs to be documented!

## Document

If you're discussing an issue and you find yourself saying "I'll have to look at this later" or "I'm not sure when I'll be able to fix this", it's likely time to document the issue as a Story in Clubhouse.

Include as much detail from the discuss to ensure whomever ends up working on the issue will have enough context to start working immediately.

## Prioritize

Prioritization is where a decision is made as to whether the work needs to be done now or can be done later. This is a very important decision as it determines whether an engineer needs to drop what they're doing to fix an issue immediately.

Prioritization should be done in coordination with at least the squad leader as well as any other stakeholders. Hopefully, most issues can be documented and prioritized to the next sprint or later, but sometimes immediate action is needed.

A Bug Story in Clubhouse is prioritized as follows: Add a label with the prioritization level: P0, P1, P2, P3 P0 = Highest priority, fix immediately P1 = High priority, fix within a few days P2 = Medium priority, fix within a couple weeks P3 = Low priority, fix later Place the story in appropriate epic

 Bugs and Fires P0 and often P1 To be fixed in the current Impact Cycle Bugs and Fires P2 and P3, sometimes P1 To be fixed in a later Impact Cycle Place the story in the appropriate Iteration Current sprint P0, sometimes P1 or P2 Highest priority issues that need immediate action Future sprint Often P1, sometimes P2 One of the upcoming sprints in this Impact Cycle No sprint P2 or P3 Lowest priority

