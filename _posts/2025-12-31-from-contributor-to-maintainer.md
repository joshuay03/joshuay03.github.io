---
layout: post
title:  "From Contributor to Maintainer"
date:   2025-12-31
categories: open-source
---

So, a few things have changed since [my last post]({% post_url 2025-07-21-open-source-has-no-deadlines-duh %}), which I 
actually ended with: 

> P.S. If it's not obvious already, I'm by no means an expert on open source, and I am not a maintainer of any large
open-source projects. I'm just a software engineer who enjoys contributing to open source in my free time. So take this
as a personal reflection rather than a generalisation.

Well, that disclaimer didn't age well. This was no longer true less than two months later. 

On the 5th of September 2025, while at the third edition of Rails World in Amsterdam, I was invited to join the Rails
Issues team. I was absolutely delighted. Shoutout to [Petrik](https://github.com/p8){:target="_blank"}, another member
of the team, for putting forward my name after noticing the contributions I've made over the years, and to
[Alex](https://github.com/ghiculescu){:target="_blank"}, also on the team and my former CTO, for backing me. Before I
knew it, I was part of the Rails teams' communications (Core, Committers, and Issues), and was given access to the
[rails/rails repository](https://github.com/rails/rails){:target="_blank"}. 

Quick note on what the Issues team actually does: we're only permitted to merge documentation changes, but we also help
with issue triage, guiding and assisting contributors, and directing attention from Core and Committers to issues and
pull requests that need it. I won't go into too much detail about the daily vibe (not literally, it's OSS after all), as
it's quite asynchronous anyway, but that's the general gist of it.

This wasn't entirely new territory, though. [John](https://github.com/jhawthorn){:target="_blank"} had given me commit
bit to Vernier the year before, so I was already helping to maintain a project that wasn't mine. But Rails was a
different scale entirely.

Then not even two months after joining, I was surprised again. On the 5th of November 2025, I was invited to be a
maintainer of Puma! [Dentarg](https://github.com/dentarg){:target="_blank"} had noticed my contributions to the project,
thought I'd be a good fit for the team, and proposed that I be invited. I loved contributing to Puma because it's one of
those projects that just *works*. It powers countless Rails applications in production, and most people never think
about it after the initial setup. But when you start digging into the internals, you realise how much careful
engineering goes into making a web server handle thousands of concurrent connections reliably. Being trusted to help
maintain something so critical to the Ruby ecosystem felt like a huge responsibility.

Just over a month later, on the 8th of December 2025, I was invited to become a maintainer of Concurrent Ruby. This one
hit differently. Concurrent Ruby is a library I'd been studying for a while, trying to understand Ruby's concurrency
primitives and how to write thread-safe code properly. Getting to work on it as a maintainer meant diving even deeper
into the parts of Ruby I find most fascinating and most challenging. It's also a project where the bar for quality is
incredibly high, which makes every contribution feel like a learning opportunity.

Looking back at my first Rails contribution and that naive expectation of a quick merge, it's wild how much has changed.
I've gone from being frustrated about waiting weeks for a review to being the person who sometimes takes weeks to review
pull requests. I finally get it. Being a maintainer isn't just about merging code. It's about thoughtful stewardship of
projects that thousands of people depend on. There are still no deadlines, and that's exactly how it should be.

---

**P.S.** I should probably update that disclaimer now. I guess I'm a maintainer of a few large open-source projects. But
I'm still just a software engineer who enjoys contributing to open source in my free time. And this is still just a
personal reflection, not a generalisation.
