---
term: Rate Limit
description: A cap on how many actions or requests are allowed in a period of time, used to prevent abuse and overload.
---

# Rate Limit

A rate limit is a cap on how many actions or requests are allowed within a set period of time. It might limit how many messages a user can send per minute or how many API calls an application can make per second. Rate limits protect systems from being overwhelmed and protect communities from bursty abuse.

## What it means

Rate limits set a ceiling on frequency. When the ceiling is reached, further actions are slowed, queued, or rejected until the window resets. They exist at two levels that matter for moderation. On the community side, they stop a single user or bot from flooding a channel. On the API side, they keep any one client from consuming more than its fair share of a shared service.

## Real-world examples

- A chat platform stopping a user from posting more than a handful of messages per second to curb [spam](/glossary/spam).
- A moderation API allowing a certain number of requests per minute per key, returning a "too many requests" response beyond that.
- Slowing repeated failed login attempts to blunt automated attacks.

## Why it matters

Rate limits are a first line of defense against floods, brute-force attempts, and runaway costs. In moderation specifically, frequency is itself a signal: the same message posted once is fine, but posted fifty times in a minute it is spam, so rate limiting and content moderation reinforce each other. For developers integrating an API, understanding the rate limit is essential to building an application that stays within its allowance and degrades gracefully when it hits the cap.
