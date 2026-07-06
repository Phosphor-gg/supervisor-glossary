---
term: Intent-Based Moderation
description: Judging the meaning and purpose behind a message rather than matching keywords or blocklists.
---

# Intent-Based Moderation

Intent-based moderation evaluates the purpose behind a message rather than the specific words it contains. It asks what the author is trying to do, such as threaten, harass, sell something, or share a personal experience, and moderates based on that answer.

## What it means

Words are ambiguous. The same term can be an attack in one message and a neutral reference in another. A keyword system cannot tell the difference because it only sees the token, not the situation. Intent-based moderation uses models that read the whole message, and often the surrounding conversation, to decide the author's goal. That decision is what drives the action, so identical words can be handled differently depending on why they were used.

## Real-world examples

- "I want to kill this boss on the last level" in a gaming server is about a video game, not violence.
- "I am going to kill you" directed at another member during an argument is a threat.
- The word "shot" is harmless in "great shot" and clinical in "I got my flu shot," but very different in a message describing intent to harm.
- Someone quoting a slur to report abuse is not the same as someone using that slur to attack, even though the text matches.

## Why it matters

Moderating on intent is what makes automated moderation usable at scale without drowning members in false positives. Systems that match keywords punish innocent messages, frustrate real users, and still miss cleverly worded abuse. Reading intent produces decisions closer to what a fair human moderator would make, which builds trust with a community and cuts down on appeals. It is the foundation Supervisor is built on, and it works together with [implicit moderation](/glossary/implicit-moderation) to catch harm whether it is stated plainly or buried in subtext.
