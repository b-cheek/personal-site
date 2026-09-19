---
title: "bcheek.dev"
description: "The why and how of my website"
summary: "The why and how of my website"
date: "2026-07-22T22:23:22-04:00"
draft: false

categories: ["Software"]
tags: ["web dev", "hugo", "cloudflare"]
series: ["Building bcheek.dev"]

cover:
  image: "Logo_of_Hugo_the_static_website_generator.svg"
  alt: "Logo of Hugo the static website generator."
  caption: "Hugo Logo"
  relative: true

showToc: true
showWordCount: true
showPostNavLinks: true
showCodeCopyButtons: true
---

## Why does this exist?

The simplest answer is that I have a lot of fun putting together new projects.

### I enjoy what I do

There are three things that tend to bring me enjoyment in software:

- Process
- Product
- Purpose

Catchy right?

#### Process

This is a little nerdy so buckle up. If you don't care for the word soup you can skip to the next paragraph.

I derive a great deal of satisfaction from finding and implementing solutions to nontrivial problems in in ways that are
idiomatic, optimal, concise, or something else I can't quite explain; writing this sentence for example satisfies some part of my brain
that wants to use specific words that inexplicably resonate with me. This does however expose a problem with my thinking,
since a sentence as baroque as that is rarely best for communication.
Whether I write software that appropriately exercises a complex design pattern, or jumps through unnecessary hoops
to be mathematically robust, it is a snapshot of my current knowledge, what interests me, my opinions on software, and more.

{{% opinion %}}
Every new project is an opportunity to express my current beliefs on how to build effective and maintainable software (and have fun 😉).
{{% /opinion %}}

There is also some joy in learning how to use a new tool, in this case Hugo.
All software tools are designed around opinions about how to write code and build software,
and each new tool gives me a chance to understand how a much smarter engineer than I may approach certain problems.
I enjoy improving, and these opportunities to learn design principles through experience are another motivation
to make little projects like this.

But there are all kinds of projects out there and, the ethos of my personal website extends beyond
"it's a thing people make and I should probably do it too."

#### Product/Purpose

These two are a little more straightforward. Aside from the process, it's fun to bring ideas to reality.
Part of that fun is getting the ideas; every now and then I have some random idea and think "I bet I could do that...",
write it down in my phone, and then get distracted thinking about how I might do it and all the things it could do.
Then if it's one of the few ideas I get to, the point where I can actually see it work feels like getting a new toy for Christmas.

I also typically have a purpose to bring some sort of utility with all the software I work on.
It can be a helpful tool for something I'm doing, making a personal site to show off all my cool work, or my favorite, money from my job!
Although a lot of stuff I work on certainly does not justify all the work that goes into it,
there are a few places where the software I make can make other parts of my life easier or more enjoyable.

### I love other things too (and talking about them)

People who have spoken to me about one of the many topics I am passionate about
have probably heard me go on and on with tangents and memories. This website gives me a place to condense all
my intense feelings into shorter (slightly? hopefully?) blurbs that I can document to look back on (or for people like you!).
I'm hoping that making these posts will inspire me to dig deeper into the things that interest me, and use them as inspiration
to create something of my own. I have lots of ideas, and if I'm lucky this website will push me to bring them to fruition.

## How did I make it?

### Hugo

Now for the easy part. To start, I am not a web developer.
However, the web tends to be a rather effective medium for making content widely available,
so I've done some work with web frameworks and other tooling. Despite some of what I said earlier in the previous section,
the _intent_ of this project is not software focused. I wanted a simple platform to present myself, and my experience
with web development has taught me that using a more complex state-driven framework will probably have me spending
more time building a mediocre, generic website rather than creating the content I want to make.
This led me to choose Hugo, a static site generator that allows me to write markdown that is rendered to HTML,
and the [PaperMod theme](https://themes.gohugo.io/themes/hugo-papermod/) for visual style. There were still a few layout overrides and quality
of life changes that I had to implement myself, but for the most part, actual web development work is abstracted away.

### Cloudflare

The final step is hosting. I've recently switched to using a Cloudflare for my web projects for a handful of reasons:

| Simplicity         | Availability & Reliability | Predictable Costs |
| :----------------- | :------------------------- | :---------------- |
| Nice dashboard     | 99.999% uptime             | DDoS protection   |
| GitLab integration | Anycast edge & failover    | Rate limiting     |
| DNS & registrar    | Well established           | No egress fees    |

Beside a few setbacks trying to make Hugo and the recently overhauled Cloudflare workers to work together,
the hosting has been a pretty painless process.

## Conclusion

I'll probably add a few more things to this site (and hopefully write about them), but for now this is my starting point.
Thanks for reading!

\- Brayden
