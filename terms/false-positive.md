---
term: False Positive
description: A case where a moderation system flags content as harmful when it is actually fine, wrongly punishing an innocent message, joke, or clinical discussion.
---

# False Positive

A false positive is when a moderation system flags or blocks content that was actually acceptable. The system said "harmful" when the correct answer was "fine." It is the error that legitimate users feel most directly.

## What it means

Every automated system makes mistakes, and false positives are one of the two ways it can be wrong, alongside [false negatives](/glossary/false-negative). A false positive punishes an innocent message: a joke gets deleted, a clinical discussion gets blocked, a quoted slur used to report abuse gets treated as abuse. Keyword filters are notorious for false positives because they match text without understanding meaning.

## Real-world examples

- Blocking "I want to kill this level" in a gaming server because it contains "kill."
- Flagging a doctor's factual message about anatomy as sexual content.
- Removing someone quoting a slur specifically to report harassment.

## Why it matters

False positives erode trust faster than almost anything else in moderation. Users who are wrongly punished feel the system is unfair, they file appeals, and they may leave. Too many false positives also bury moderators in overturned actions and make a product feel broken. Reducing them without letting real harm through is the central tradeoff in moderation, and it is why [intent-based](/glossary/intent-based-moderation) systems that understand context outperform blunt keyword matching. The balance between false positives and false negatives is measured with [precision and recall](/glossary/precision-and-recall).
