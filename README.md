# RLPM - The Roblox Lua Package Manager

## About

``RLPM``, the **R**oblox **L**ua **P**ackage **M**anager, is an application
that aims to foster code reuse and library distribution on the Roblox platform.
It does this by providing both a deployable server which can be queried for
"packages", and a corresponding client that runs in the user's Roblox Studio.

## Goals / Synposis

*As a disclaimer, the last I've been seriously involved in Roblox was many years
ago, but after asking some people it seems like the situation is essentially
the same as it was back then.*

``RLPM`` aims to solve the code reuse problem that plagues project development
on the Roblox platform. From my own experience in both creating things,
observing others create things, asking people I know who create things, and
occasionally looking around the Scripting Helpers forum, I've found that, 1)
essentially every developer or development studio rolls its own code, and 2)
many problems being encountered by developers and development studios are
duplicates, leading to each studio having its own unique solution to a common
problem.

Point #1 is responsible for a huge amount of time that is wasted duplicating
work -- time that a developer or development studio could otherwise be spending
developing what makes their project actually interesting and what is actually
visible to the end-user. In other words: the stuff that actually matters.

Point #2 is responsible for a more wide-reaching problem: because every
developer or development studio rolls their own solutions to common problems
and does not publish their advancements, an environment is created where
everyone is essentially trying to re-invent the wheel. Collaboration is
important to solving complex problems: when programmers who each specialize in
the production of certain procedures combine their efforts, a product is formed
that is far greater than what could have been produced by any of the individual
programmers on their own.

Game development teams understand this, but their libraries are limited to the
small microcosm of that team and people who work with it, where they are prone
to rot away and stagnate after the developers decide to move on. In the real
world, someone or a group of people who found that project to be useful would
have continued on the work, but in Robox no such culture exists.

### The solution

An assumption that this project makes is that the reason for these problems is
because of the following issues having to do with code reuse on Roblox, and if
we can resolve as many of these as is possible, then a healthy culture of code
sharing and reuse should follow:

1. **Quality control**: Due to the prevalence of "viruses", developers are
   justifiably anxious to use things made by other people. A centralized,
   peer-reviewed authority from which developers can reliably retrieve quality
   code would solve this issue.
2. **Ease of updates**: There is no way to see if an asset that is inserted
   from Free Models has been updated without going to that asset's page and
   checking. As a package manager, ``RLPM`` will aim to make updating easy,
   with the rolling back of packages being a goal for the future.
3. **A general distrust of "open source" assets**: This is a harder problem to
   solve. This issue is rooted in both issue #2 and a general attitude of
   elitism fostered by the Roblox developer community. I hope that, with the
   support of reputable developers, ``RLPM`` will be able to demonstrate that
   sustainable development communities can be made possible on Roblox.
4. **Developer habits**: As many Roblox developers are first-time programmers,
   there is a tendency to not follow good practices for modularity and code
   reuse. I hope that, if ``RLPM`` becomes popular, it can bring visibility to
   this problem and possibly even solve it just by virtue of being there as a
   tool that programmers can use.

Whether we can be successful at fixing code reuse on Roblox remains to be seen,
but it's sure worth a try, at least in my opinion.

## Roadmap

TODO

## Contributing

As I no longer have convenient access to a computer that can run Roblox Studio,
the ``RLPM`` client application will probably start to rely on those who do as
time goes on. If you're interested, shoot me a direct message
[@ecilicica](http://twitter.com/ecilicica). Thank you!
