# Estimating

## Estimating is hard

Consistently estimating the time it will take to implement even small and well understood software components is impossible with any degree of accuracy. Software engineering is a creative endeavor, with very few constraints on possible solutions. Even then, valid solutions are very often not valid for long as the problem itself often changes and morphs over time.

Yet, estimating is very important in order to plan work, manage resources and set expectations. The paradox of estimating being important, yet impossible, may someday be solved, but is still, at best, a work in progress and requires compromises to be effective.

There are always important considerations for engineers to make effective use of estimating:

#### The haze of time

We're all familiar with the phenomenon of haze, where objects that are far away appear hazy and are sometimes completely obscured relative to nearby objects. The same effect applies to estimating in that it is more difficult to estimate outcomes the further away they are in the future.

A task that you are going to do within the next couple of weeks is likely something you've already thought through to some extent or at least have some understanding of the context. A task that won't or can't be done for a longer than a few weeks or months is likely much less well understood.

To account for the haze of time, it should be understood that estimates can be more precise for tasks that are about to be done and less precise for tasks off in the future. More specifically, estimates for tasks or timelines that fall within the next 2-3 weeks should be more trustworthy than tasks beyond that window. In fact, estimates made beyond the 2-3 week window should be expected to change as the tasks grow closer.

#### The moving target

That software is almost infinitely malleable is both a blessing and a curse. Even the most well conceived solutions can often be judged as completely missing the mark after or sometimes during implementation. At best, all solutions tend to evolve rapidly over time as feedback is incorporated from stakeholders.

Given that software solutions are the result of many small iterations, precise estimations are impossible. Therefor, estimations should be made with wide margins. Hours are typically too precise to be accurate and weeks are typically too imprecise to be useful. Estimating using number of days is a good compromise.

## How do I estimate a story in ClubHouse?

The estimating scale in ClubHouse is in days \(where 1 point = 1 day\) and the range is:

1 - This is a small task and can be done quickly \(Should have a relatively small number of these\)

3 - This is a normal sized task that'll take a few days \(Should mostly have these\)

5 - This is a a larger task that'll take about a week \(Okay to have many of these\)

10 - This task is _probably_ too big and needs to be split into smaller tasks \(Should minimize these\)

* For the current sprint, all stories _must_ be accompanied by an estimate
* For all other stories, if the scope is well-defined, an estimate can be added
* It's okay to leave the estimate blank for stories on the backlog if there are many unknowns
* Estimates for work in progress shouldn't be modified. This misses the point!
* Engineers should get in the habit of comparing estimates to actuals to adjust their intuition

## FAQ

### Should I consider the time it takes to get approvals when estimating a story?

Nope, just estimate the time you'll be working on it. If you're waiting on something for more than a day, you can move the story to blocked, but the estimate should be the time it will take you to implement the story assuming you don't have to wait long for dependencies.

### How is estimating helpful if it's so inaccurate?

In aggregate, estimates tend to 'average' out to numbers that are a little more accurate that the individual estimates themselves. These aggregate estimates can...

* give rough figures for timelines on larger initiatives
* provide clarity on resourcing needs
* identify hotspots in the architecture where lots of work is being done

