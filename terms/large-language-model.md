---
term: Large Language Model (LLM)
description: An AI model trained on vast amounts of text that can understand and generate human language, and the technology behind modern intent-based moderation.
---

# Large Language Model (LLM)

A large language model, or LLM, is an artificial intelligence model trained on enormous amounts of text so that it can understand and generate human language. LLMs are the technology behind modern chat assistants, and they are increasingly used to power moderation because they grasp meaning rather than just matching words.

## What it means

An LLM learns statistical patterns of language from its training data, which lets it predict and produce text, answer questions, summarize, translate, and classify. For moderation, the useful property is comprehension: an LLM can read a message and judge what it means in context, including tone, sarcasm, and [implied](/glossary/implicit-moderation) harm, rather than scanning for forbidden tokens. That is what makes [intent-based moderation](/glossary/intent-based-moderation) practical.

## Real-world examples

- A model that reads a full sentence and decides whether "I will get you" is a threat or a friendly promise, based on context.
- Purpose-built classifiers, like Supervisor's models, that specialize in scoring content against moderation categories rather than open-ended chat.

## Why it matters

LLMs moved moderation from brittle keyword rules toward systems that understand language the way people do. That means fewer [false positives](/glossary/false-positive) on innocent messages and better detection of disguised abuse. They are not magic: they can be wrong, they can be manipulated through [prompt injection](/glossary/prompt-injection), and they cost more to run than a simple filter. But for judging meaning at scale, they are the current state of the art, and understanding what they are helps explain why modern moderation is so much more capable than the blocklists that came before.
