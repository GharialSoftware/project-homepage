---
title: "We should stop duplicating proprietary services"
description: "Thoughts on the problematics leading the Gharial project"
summary: ""
date: 2025-04-24T01:00:00-05:00
lastmod: 2025-04-24T03:00:00-05:00
draft: false
weight: 50
categories: []
tags: []
contributors: ["Nicolas Constant"]
pinned: false
homepage: false
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
  noindex: false
---

> This article is part of a series of blog posts aimed at developing ideas and vision defining the DNA of the Gharial project. 

The first important set of software we saw on the Fediverse were mostly inspired by proprietary and successful online services. And today the global landscape of the Social Web is mostly driven by those mirrored services: 

* **Mastodon**: Twitter alternative
* **Peertube**: Youtube alternative
* **Pixelfed**: Instagram alternative
* **Mobilizon**: Meetup alternative
* **Lemmy**: Reddit alternative
* **Bookwyrm**: GoodReads alternative
* **WriteFreely**: Medium alternative

And a lot of forks and similar projects.

While it makes a lot of sense to take inspiration from what already works, making it FLOSS (*Free Libre and Open-Source Software*) and try to fix some issues during the process, we also should consider that doing so can also brings some unquestioned design flaws in its wake. 

Especially when some of those flawed designs became "canonical" due to their wide adoption, leaving them even more unquestioned.

Another issue of duplicating some existing product is the lack of differentiation and originality of the proposal: by design, those new softwares already come into a field where there is already (at least) a well-established big player and therefore become a de facto competitor and prone to immediate comparison.

Of course, duplicating existing services also have its merits and strength: there is no need to explain the new service to newcomers, and the adoption can be easier than something truly original and never experienced before.

While I don’t thing the Fediverse followed the wrong path here, I also strongly believe that there is an unexploited potential that is currently unmet by the current landscape.

But first, let me unpack a bit more the previous claims I’ve made:


## Proprietary software’s flaws and toxicity leaks into our work when we copy them

While a lot of the current social media landscape’s toxicity is wildly documented and available out there (hell, there is even *Netflix* content about it!), I will focus in this section on the small things, the harmless and innocuous *at-first-sight* characteristics that we take for granted today and replicate without questioning them. 

There would be a lot to cover here, but for the sake of the argument and food-for-though, I will use the case of ***social metrics*** as an illustration.

Social metrics seems to be a granted functionality those days: how much followers do you have, how much content did you post, how many likes, views, shares, your content generates, etcetera. 

On a technical point of view, it surely is tempting to bring those metrics to the user interface. A single SQL request on preexisting data and here we go, a new nice and shiny gizmo to display!

And having some numbers is always cool after all. It feels *professional*, it gives feedback and sense of control.

Unfortunately, this is far from neutral and brings with its integration a whole set of behaviors and values.

First, if applied to people, it ends characterizing them, consciously or not, numbers do have influence and impact. 

For example, having a lot of followers can be seen as a social signal that you’re important, meaningful. That can change the way you behave, as much as how people interact with you.

And that why we can see hoarding temptation and even massification seeking behavior based on those metrics. Some people will seek to increase those numbers and even work actively toward the sole mean of increasing it. On some platform, some might even buy those metrics to claim a social status.

But... that’s not why we’re here, right? We’re here to share, to chat, to discover, to debate, to have fun, not to compete in a big numbers contest. How those metrics can be relevant in our space?

On proprietary platforms, this functionality makes a lot of sense: you need engagement to sell [available human brain time]( https://en.wikipedia.org/wiki/Criticism_of_advertising#cite_ref-43:~:text=For%20an%20advertising%20message%20to%20be%20perceived%20the%20brain%20of%20the%20viewer%20must%20be%20at%20our%20disposal.%20The%20job%20of%20our%20programmes%20is%20to%20make%20it%20available%2C%20that%20is%20to%20say%2C%20to%20distract%20it%2C%20to%20relax%20it%20and%20get%20it%20ready%20between%20two%20messages.%20It%20is%20disposable%20human%20brain%20time%20that%20we%20sell%20to%20Coca%20Cola) to advertisers, and this kind of grind game incentivise your users to stay and even work for your service. People will try to engage on trending topics even if it doesn’t interest them for the sole reason of increasing their social metrics, will participate on viral conversations even if they despise the subject, and so on.

But on the open social web, where the focus of our work is toward the users themselves, is bringing those metrics in really a good idea? 

I’m convinced that we brought this functionality in because it was part of the original offering, and to create a "same thing but FLOSS" software, it just felt natural to keep it. Not because we strongly believe it was a good idea after a throughout and detached analysis. 

And maybe we should do a similar analysis on many other aspects that defines those proprietary platforms, especially when they’ve become usual and sometime even part for the local culture, and that it’s easy and tempting to import it without questioning it.


## FLOSS should be a mean, not an end

As a developer myself, I understand the stance and temptation to label code as FLOSS and call it a day.
But I think we should look forward the question of licensing. 

First because - and pardon my French here - people don’t give a fuck about licensing. And in a way they’re right about it. 
If a service gives an inferior experience compared to other alternatives, it’s a hard sell to justify its value only via its license, the end-user is mostly not a programmer and licensing doesn’t impact them much.

I strongly think that the FLOSS conversation should be more of an explanation than anything else, that we should only speak about it when people question how we managed to provide the software/service itself. It’s a mean, not an end. 

For example, in the case of Mastodon, it’s the claim that people can possess the tools of creating and managing their community that is guaranteed by FLOSS licensing, and we should always insist on the former than the later.

On this side, I also think the value provided by the current landscape is weaker than it could be, and it was illustrated by Meta’s *Threads* service entering the space: people were afraid of the impact of such service, and that they might end Embrace/Extend/Extinguish the Fediverse.

If we fear that an actor could perform such hostile operation, it just means that the value and experience of the Fediverse isn’t sufficiently anchored in what FLOSS can permit (sovereignty, interconnectivity, etc).

The best warranty of resilience we can obtain is by making sure that the first characteristic of the Fediverse is the access to all the compatible services and communities. That way we will ensure no-one will be able to takeover the space, since the way the space operates is the distinctive and inherent value.

Even better: we should try to create services and software that couldn’t be replicate in the proprietary space, offering a user experience impossible to experiment with privative networks. 

Hence bringing something truly original to the table and ensuring our independence and resilience.


## The Open Social Web as a peaceful experience

In the current “FOMO” and hyper-competitive space that BigTech’s service provides, there is a nice and easy way to fundamentally distinct the Open Social Web to make it more attractive: offering the opposite experience.

If we look back at the good old 2000’s web, people were following this path: checking blogs and websites to see if new content were published was tedious, so we invented RSS feeds, aggregators, etc. The idea was to remove pressure and make our life easier and less prone to FOMO.

That also explain why many of us didn’t understand the attractiveness of Facebook or Twitter as a RSS replacement at that time, since it reintegrated those bad aspects (but to be completely fair, it was only because RSS was only known and used by power users, we also failed on the vulgarisation field).

Also, being on the Fediverse since 2017, here is some observations I’ve made: 

* I’ve never really seen newcomers being fond of the decentralized aspect: it increases the onboarding complexity with few advantages at first sight.
* But on the other hand, newcomers - after some time - are amazed by the more appeased and calm space the Fediverse is, and that’s what ultimately make them stay.
* "Big profiles" from other platforms usually come, applies their common posting habits to get traction (often by posting overly polarised and outraged content) that usually game positively the algorithm elsewhere, only to see that doesn’t work here and leave.

These observations are interesting since it was very common to promote Mastodon as a Decentralized Twitter alternative, but decentralization is a necessary evil that degrades the newcomer’s onboarding, and people finally stay on the service because it’s not one of those services where you’re almost invisible if you don’t like surfing on the dopamine-boosted outraged bandwagons.

In fact, marketing Mastodon as a ""Peaceful Twitter"" (or something conveying the same idea) may have been more adequate, since the inner value of it is to not provide the toxicity and FOMO of the later. And the "explanation" on "how" Mastodon successfully manage to do this would be all the talking about decentralization, lack of toxic algorithm and so on (for those interested, and clearly, not everyone seems interested to learn about those details).

Sure, nothing’s perfect, and we do have our share of drama and so on, but those are way more natural and not actively promoted and rewarded by the system itself.

And I’m convinced this is the way forward: we should continue working on how to increase the peacefulness of the space, how to make it more enjoyable, less time-consuming and more respectful of the end user’s attention.

Sure, doing so will not provide services as engaging and addicting as other’s Big Tech products, but that’s a feature, not a bug. And it should definitively be our end-goal.

I aim to create Gharial with all those thoughts in mind.

I would love to get your opinion and feedback; do you agree with this analysis? What does it inspire you? Do you have insights you’d like to share with me? 

Feel free to reach me directly at [@gharial@mastodon.social](https://mastodon.social/@gharial), or discuss directly under [the post on mastodon](https://mastodon.social/@gharial/114396530696547979).
