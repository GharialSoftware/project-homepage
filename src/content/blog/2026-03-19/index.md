---
title: "2nd Layer Fediverse Software"
description: "A draft of a new kind of Fediverse Software"
summary: ""
date: 2026-03-18T01:00:00-05:00
lastmod: 2026-03-18T05:00:00-05:00
draft: true
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

<br/>
Under this <i>2nd layer</i> designation, I'd like to draft a new kind of Fediverse software. Draw the global concept, trace boundaries and give a common ground via a shared vocabulary related to it.

## What is a 1st layer Fediverse Software? 

First things first. Let's define properly what a 1st layer Fediverse Software might be and how we could categorize it properly.

Let me throw some raw characteristics that would characterize a member of the 1st layer: 

*	The software enables publication of original content (text, photo, video, etc.) that is hosted on the same service
*	The software also hosts the accounts authoring the content
*	If the Federation is disabled, the software can still provide the service and only the scope of the federation is lost by this action

With those succinct characteristics, it might already appear to you that most current Fediverse software belongs to this 1st layer:

*	Mastodon permits the publication of micro-blogging content, authored by the accounts it hosts, and if Federation is cut down, it remains a functional micro-blogging platform.
*	Pixelfed is the same, but for pictures.
*	Peertube is the same, but for videos.
*	Mobilizon is the same, but for meetings planning.
*	WriteFreely is the same, but for long blog post.
*	Etc. 

1st layer Fediverse Software should be the normal entry point for newcomers to the network, a natural host of identities and providing publication capabilities. It's the most important part of the network, being the foundation of it.


## So… what would be a 2nd layer Fediverse Software?

As the "2nd" implies, this second category would stand on the foundation of the 1st. So, with no longer due, let me draft again some characteristics of this envisioned category: 

*	The software doesn't need to (and often won't) enable original content publication
*	The software doesn't host the accounts authoring the original content
*	The software might provide identities/accounts that would interact with 1st layer content
*	If the Federation to the 1st layer is disabled, the software becomes totally useless; but it can still be usable and relevant if only 2nd layer's Federation is disabled.

Of course, the definition of this 2nd layer is wide and loose enough to open the doors of a full set of new services. But to sediment this bare definition, let me draft an example of a 2nd layer Fediverse Software and how it could materialize in the network.


## Example: Curation of content

An obvious example that would fit perfectly this 2nd layer definition would be an app specializing in content curation.

One (if not the most) interesting functionality of the Medium's platform is the concept of Medium's [publication](https://help.medium.com/hc/en-us/articles/115004681607-Getting-started-with-a-Medium-publication): those are shared spaces aiming to centralize posts from other accounts evolving around a common theme or topic. 

This concept of a central point of publication where authors could converge and federate is important since it holds a lot of value for both the writers and the readers: 

*	Readers interested in a certain kind of content could find publications that meet their interests very easily, and once they find a publication that fits their taste, it will be even easier for them to discover new authors and texts that they enjoy
*	Writers don't need to beat an algorithm (by investing their time and/or money) to get visibility to the public: they only need to fit the publication's editorial line

Of course, this concept isn't new, and we can find numerous examples in our history like how poets in the late 19th century gathered in bars and shared their work via their own publications.
It is for me - by far - the most viable and interesting way to convey an artistical vision while also being accessible to the public. 

Interestingly, this is a concept that is currently mostly absent in the Fediverse space. I don't really know why, and I must admit it always puzzled me when a Fediverse Software defined itself as a Medium clone, while missing this important part and only being focused on the content publication aspect.

But the good news is that due to how the Fediverse is built today we have multiple ways to post long text content: Plume, WriteFreely, Wordpress with ActivityPub plugin or even micro-blogging platform that accept long posts. 

All those are 1st layer Fediverse Software. 

What if we provide an instance that would mimic a Medium publication and would be dedicated to the curation and aggregation of "German Poetry evolving around nature"? Various authors publishing their content on their own Fediverse platform and having some text related to this theme would be able to submit their work, and if it were selected, it would be visible for every follower of this publication.

Interestingly, this "publication" entity could materialize itself as a Fediverse Account and would be backyard compatible to 1st layer software and accounts that would be able to follow it back.

This Fediverse Publication could be managed by a single person, a group of people, an algorithm, or even left completely unmoderated (I can imagine some kind of art's experiment where it could make sense), and the way the curation is made would attract a different kind of public and creators.

## Federation between 2nd Layer Fediverse Software

While different from the federation between 1st and 2nd Layer Fediverse Software, Federation between two 2nd Layer Fediverse Software will be possible (while not as critical and the first one) but might work a bit differently than we are accustomed to on the network.

Let's take back our example of the "German Poetry evolving around nature" publication back: imagine that this publication ends to be very successful and a lot of content is published every day, well that's good news for people eager for this content, but what if I'm only interested in a sub-part of this theme? Like "Medieval German Poetry evolving around nature"? 

Well, I could start a new instance/publication dedicated to this topic, and federate content from the first one, and curate it again so that only the Medievalist poem goes through. Materializing a new point of rally for people interested in this particular and very specialized topic.


## Conclusion

I hope this example helped you to grasp the idea behind what I'm referring to “2nd layer Fediverse Software”. But keep in mind that other kinds of application than the example if developed should be able to meet the same characteristics, and I'm curious what service people might imagine would also fit that definition. 

I didn't really develop the value of this kind of application here, since I wanted to keep it somewhat short and focused on the definition itself. But be assured I'll develop those aspects in another post.
<br/>
<br/>
<br/>
Oh, yes, I'm sure you've guessed it already, but Gharial will be a 2nd Layer Fediverse Software.
<br/>
<br/>



I would love to get your opinion and feedback. What does this concept inspire you? Do you have insights you'd like to share with me? 

Feel free to reach me directly at [@gharial@mastodon.social](https://mastodon.social/@gharial), or discuss directly under [the post on mastodon](https://mastodon.social/@gharial/).
