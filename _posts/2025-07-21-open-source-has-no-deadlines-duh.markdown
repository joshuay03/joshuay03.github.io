---
layout: post
title:  "Open Source Has No Deadlines, Duh"
date:   2025-07-21
categories: open-source
---

Recently, I was reflecting on how I got started contributing to open source. About three years ago, I was in my first
full-time job as a software engineer, approaching the end of my six-month probation period. I was settling
in—contributing to some decently sized projects and generally getting the hang of things. But despite that, I was
getting bored.

As a fresh graduate, I had way too much energy and couldn't shut my brain off after work. This led to a bad habit of
going on work-related side quests in the evenings. Eventually, I realised I needed something else to scratch that itch.
Thinking about work after work wasn't the answer—I needed a new challenge.

At the time, I had been using Ruby on Rails for just over a year. I was first introduced to it during an internship in
my final year of university, where I had to learn it on the job as more frontend-focused tickets (CoffeeScript +
AngularJS) were assigned to me, requiring minor changes to the Rails API. But I had never actually sat down and read
through the guides from start to finish, watched tutorials, or even built a project from scratch. So I decided to spend
my evenings learning everything I could about Rails—especially how it worked under the hood.

A couple of days in, I had the Rails GitHub repository open in my browser, casually browsing open issues out of
curiosity. That's when [one of them caught my eye](https://github.com/rails/rails/issues/44986). It stood out because I
understood the problem immediately—partly thanks to the author's great reproduction script, but also because I had just
finished reading the Active Record guide. I had a fresh understanding of how polymorphic associations and association
autosaving were supposed to work, and I had just used these features when working on a feature at work. I thought to
myself, *I think I can fix this!*

I won't go into all the details, but let's just say it took a lot longer than I expected. The Rails codebase is big, and
although it's quite well-organised, it can be overwhelming to navigate as a newcomer. Regardless, it was an awesome
learning experience, and I ended up sending a pull request for what would become
[my first Rails contribution](https://github.com/rails/rails/pull/45298).

What I want to focus on are some expectations I had going into this. When I started working on the issue, it had already
been open for almost a month, so I was surprised that no one had commented on it yet. In my naiveté, I thought, *This is
a bug in a core part of the framework—if I'm taking it on, I need to fix it ASAP!* So when I finally put up my pull
request, I expected it to be merged within a day or two. I received a review from a Rails team member and then...
nothing. I waited a week. Then another. Eventually, I kind of forgot about it.

At some point, one of the founders of the company I was working for—who was also a member of the Rails Issues
team—noticed my pull request and shared it in the company chat. He mentioned that there was a Discord server where I
could ask for a review if my pull request had been open for a while.

And here's where I have to admit I made another noob mistake: turns out there's a whole
[contribution guide](https://guides.rubyonrails.org/contributing_to_ruby_on_rails.html) that explains all of this,
including a link to the
[Discord server](https://guides.rubyonrails.org/contributing_to_ruby_on_rails.html#get-some-feedback). But I was so
excited about contributing to Rails that I just jumped in headfirst without reading any of it.

I joined the Discord server, asked for a review, and got some great feedback. I addressed the requested changes, and my
pull request was merged shortly after. I was ecstatic. I had contributed to Rails! I was now a Rails contributor! I was
part of the Rails community! I was part of the open-source community!

However, I kept thinking about how long it had taken for my pull request to be merged. In hindsight, I think the problem
was that I was treating it like a work project. I had picked an arbitrary deadline and expected myself to meet it. I was
thinking about the users of the framework as paying customers waiting for a bug fix they had reported through support. I
was thinking about the Rails team and other contributors as colleagues responsible for reviewing my work in a timely
manner.

I had created this false sense of urgency in my head, as if this mature and stable framework was going to fall apart if
my pull request—or any bug fix pull request for that matter—wasn't merged within a week. I was so wrong. I was so naïve.

The thing is, I didn't really learn this lesson until much later. I continued to contribute to Rails and other projects,
and I would notice the same pattern almost every time. Some pull requests would be merged within a day, others would
take weeks, and some would take months. It also varied greatly depending on the project. I didn't really care too much
about it, though, because I was just enjoying the process of contributing. I was learning so much, and I was having fun
doing it. But now, looking back, I realise that this is just how open source works. There's nothing inherently good or
bad about it—it's just the way it is.

It took me a while to understand that most open-source projects are simply passion projects. And more importantly, [they
are gifts](https://world.hey.com/dhh/open-source-is-neither-a-community-nor-a-democracy-606abdab). I'm actually amazed
that so many people are willing to spend their free time working on and maintaining these projects. They don't owe me
anything. They don't owe anyone anything. They are doing it because they want to, because they enjoy it, because they
believe in it. I know that for larger projects like Rails, there are some people who are paid to work on them, but even
then—it's still a gift to the community.

---

**P.S.** If it's not obvious already, I'm by no means an expert on open source, and I am not a maintainer of any large
open-source projects. I'm just a software engineer who enjoys contributing to open source in my free time. So take this
as a personal reflection rather than a generalisation. Also, there are many great write-ups and talks out there about
how open source projects should be managed, how to make them sustainable, and even how to build business models around
them. I encourage you to seek those out if you're interested in learning more about the topic.
