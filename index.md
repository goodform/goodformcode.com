---
layout: default
---

# What is this?

With the [recent licensing changes](https://sfconservancy.org/blog/2018/aug/22/commons-clause/) to several [Redis Labs modules](https://redislabs.com/community/licenses/) making them no longer free and open source, GNU/Linux distributions such as [Debian](https://www.debian.org/social_contract#guidelines) and [Fedora](https://fedoraproject.org/wiki/Licensing) are no longer able to ship Redis Labs' versions of the affected modules to their users.

As a result we have begun working together to create [a set of module repositories](https://github.com/goodform) forked from prior to the license change. We will maintain changes to these modules under their original open source licenses, applying only free and open fixes and updates.

We are committed to making these available under an open source license permanently and welcome community involvement.

## How can I help?

1. Contribute to [our GitHub repositories]({{ site.github_url }}).

1. Share this page and spread the word about the "Commons Clause" more generally, for example by [tweeting a link to this page](https://twitter.com/intent/tweet?url=https%3A%2F%2Fgoodformcode.com%2F&text=GoodFORM%3A%20Free%20and%20open%20Redis%20modules&hashtags=redis).

## Who is involved?

 * [Chris Lamb](https://chris-lamb.co.uk) &lt;lamby@debian.org&gt;<br>
 * Nathan Scott &lt;nathans@fedoraproject.org&gt;

## What about security updates?

It is conceivable that reimplementing or merging security-related fixes that are now released solely under the "Commons Clause" license could be problematic.

However, in our experience the vast majority of security fixes are trivial enough to be not subject to copyright law (eg. off-by-one-errors, calls to sanitise user input correctly, etc.). In contrast, fixes that are highly invasive (SPECTRE/Meltdown mitigation or the recent issues around various algorithms in GnuPG) which would be subject to copyright are relatively rare in comparison.

One exception could be the testcases to patches which are clearly of value in the security production cycle to prevent future regressions and to ensure you are actually fixing the issue at hand.

## How can I find out more?

Please see the following links:

 * ZDNet: [Redis Labs and Common Clause attacked where it hurts](https://www.zdnet.com/article/redis-labs-and-common-clause-attacked-where-it-hurts-with-open-source-code)
 * LWN.net: [Redis modules and the Commons Clause](https://lwn.net/Articles/763179/)
 * The Register: [Redis has a license to kill: Open-source database maker takes some code proprietary](https://www.theregister.co.uk/2018/08/23/redis_database_license_change/)
 * TechRepublic: [Why Redis Labs made a huge mistake when it changed its open source licensing strategy](https://www.techrepublic.com/article/why-redis-labs-made-a-huge-mistake-when-it-changed-its-open-source-licensing-strategy/)
 * Drew DeVault: [The Commons Clause will destroy open source](https://drewdevault.com/2018/08/22/Commons-clause-will-destroy-open-source.html)
 * [Redis](https://redis.io): [Remove Commons Clause modules (#984)](https://github.com/antirez/redis-doc/pull/984)
 * iTWire: [Debian dev forks Redis modules that are under Commons Clause licence](https://www.itwire.com/open-source/84888-debian-leader-forks-redis-modules-that-are-under-commons-clause-licence.html)
 * Late Night Linux Podcast: [Episode 48](https://latenightlinux.com/late-night-linux-episode-48/) (7m15s &rarr; 12m20s)
