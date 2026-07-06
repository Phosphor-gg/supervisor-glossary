---
term: Moderation Labels
description: The categories a moderation system assigns to content, such as harassment, hate, or spam, describing what kind of harm was detected.
---

# Moderation Labels

Moderation labels are the categories a moderation system assigns to a piece of content to describe what kind of harm it detected. Rather than a single pass or fail, a message receives one or more labels that explain why it was flagged, which lets a platform decide how to respond to each type of violation.

## What it means

A good moderation decision is not just "bad" or "fine." A platform usually wants to treat a scam differently from a personal threat, and treat profanity differently from hate. Labels make that possible. Each flagged message is tagged with the specific categories it matches, so the same engine can power a strict server that blocks profanity and a relaxed one that only cares about threats and scams.

## Supervisor's labels

Supervisor classifies content across a fixed set of categories, including:

- Profanity, Toxicity, Insult, and Harassment for interpersonal abuse
- Hate and Racism for identity-based attacks
- Sexual, Sexual (Explicit), and Sexual (Unlawful) for adult and prohibited sexual content
- Violence, Self-Harm, and Medical or Injury content
- Sensitive Content for material that needs care
- Spam, Promotional, and Scam for unwanted or deceptive messaging
- Illegal Activity for content describing unlawful acts

## Real-world examples

- A message insulting another member might be labeled Harassment and Insult at once.
- A crypto giveaway link could be labeled Scam and Promotional.
- A slur aimed at a group would be labeled Hate or Racism, whether it is spelled out or [implied through code](/glossary/implicit-moderation).

## Why it matters

Labels turn moderation from a blunt switch into a configurable policy. They let each community enforce its own standards from one shared engine, give moderators a clear reason for every action, and make audit logs meaningful. They also make thresholds tunable per category, so a platform can be strict about threats while tolerating mild profanity. Without labels, a flag is just a flag, and nobody can tell why the system acted or tune how it behaves.
