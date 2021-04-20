---
title: Mapping an Inbox UX
description: This is a post on My Blog about win-win survival strategies.
date: 2018-08-24
cardbg: "#ebf9eb"
cardtext: "#0ca750"
tags:
  - idea
layout: layouts/post.njk
---

Work in the Inbox is centered around messages. There are two primary dimensions to consider when thinking about message work: amount of messages and depth of focus required. Using these two dimensions, we can map existing features and spot opportunities for new features.

![ux map of inbox features](/img/inbox-map.png)

## From many to one
One of the core promises of our product is the ability to manage all of your company’s social profiles in a single place. This, of course, often results in a very large number of messages coming into our users’ inboxes. Because their work requires them to assess each message, this process of moving from working with many messages and then narrowing down to a single message becomes a defining dimension of the inbox experience.

## From shallow to deep
Some inbox work happens in less than a second, other moments of action require more time and focus to complete. For example, identifying a “spammy” comment and immediately clearing it from your inbox takes less focus and effort than answering a detailed customer question in the form of a Direct Message. Our users have described this shifting change of required focus as “zooming in and out.” 

## Mapping against these two dimensions
If we take these two dimensions (amount & depth) we can map the Inbox’s current feature set into four distinct quadrants (with four general purposes):

- Many messages, shallow work (organization)
- Many messages, deep work (connection opportunities)
- One message, shallow work (shepherding/processing)
- One message, deep work (connection building)

## Organizing
This quadrant is mostly focused on delivering the core Inbox promise of “right message at the right time.” These features organize, prioritize, and present messages to users how they need them, when they need them. Spike Alerts call attention to an emerging high-volume event and focus attention on messages related to the spike. Inbox Views allow users to save useful sets of filters that provide clear focused workspaces for particular sets of responsibilities.

## Shepherding
As work moves from many messages to a single message, we encounter the shepherding or processing type features. Though these actions are shallow (requiring relatively less focus that other actions) and can happen quickly, they comprise the largest set of actions taken in the app by far. Sprout ingests billions of messages—and we see millions of completion actions taken every year. It also becomes clear that processing and organizing go hand-in-hand—with these particular features being the mechanism for manual organization (e.g. Completing messages gets them out of a user’s view so they can focus on more important messages).

## Connection Opportunities
Interestingly enough (given its name), this quadrant appears to present the largest product opportunity in terms of our feature-set. Working with many messages with deep focus is where we start to see analysis happening. Profile Views present our users with a larger picture of an individual’s social activity—providing a bird’s eye view of historical social activity in a way that allows for strategic decisions to be made about how to interact with someone.

## Connection Building
The bread and butter of the Sprout Inbox experience—deep, single message work is where we see one-to-one human connection happening. This type of work is most vividly demonstrated in the Reply experience—specifically Twitter DMs. By the time our users arrive at this point in their workflows, they’ve gone from assessing hundreds of messages to zooming in on just a single person with a single question. We invest heavily in the part of the flow because this is where human connection happens. We want this to feel as responsive and satisfying as possible. User trust is very important in this quadrant!