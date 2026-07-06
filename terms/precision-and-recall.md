---
term: Precision and Recall
description: Two metrics that measure moderation accuracy: precision is how often flags are correct, recall is how much harm is caught.
---

# Precision and Recall

Precision and recall are the two core metrics for measuring how accurate a moderation system is. Precision measures how often the things it flagged were actually harmful. Recall measures how much of the real harm it managed to catch. Together they describe the two ways a system can succeed or fail.

## What it means

- High precision means when the system flags something, it is usually right. Low precision means it cries wolf, producing many [false positives](/glossary/false-positive).
- High recall means the system catches most of the harm that exists. Low recall means a lot slips through as [false negatives](/glossary/false-negative).

The tension is that pushing one up often pushes the other down. A system that flags everything has perfect recall and terrible precision. A system that flags almost nothing has high precision on the few things it catches but terrible recall.

## Real-world examples

- A strict keyword filter might have high recall on the exact words it lists but low precision, because it also blocks innocent uses of those words.
- A cautious system tuned to never annoy users might have high precision but low recall, quietly missing disguised abuse.

## Why it matters

Precision and recall give a platform a shared, honest language for the central tradeoff in moderation. Instead of arguing about whether a system is "good," teams can set targets: how many false positives are tolerable to catch a given share of real harm. Being able to tune this balance per [label](/glossary/moderation-labels), strict on threats and lenient on mild profanity, is what separates a usable moderation product from a blunt one.
