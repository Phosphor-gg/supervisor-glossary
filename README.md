# Supervisor glossary

Markdown sources for [supervisor.gg/glossary](https://supervisor.gg/glossary).

The website builds the glossary from this repo: a pre-build step clones it,
renders every term to HTML, and generates the alphabetized index, so
publishing a term is adding a markdown file here and rebuilding the website.

## Conventions

- Terms live in `terms/<slug>.md`; the filename is the URL slug
  (`terms/spam.md` becomes `/glossary/spam`).
- Every term starts with frontmatter:

```yaml
---
term: Term Name
description: One-line definition shown on the index and in meta tags.
---
```

- `term` is the display name; the index sorts alphabetically by it.
- Quote any frontmatter value containing a colon.
- Standard markdown plus tables and fenced code blocks. Start the body
  with a `# Term Name` heading.
- Entries read like short articles: a plain-language definition, what it
  means, real-world examples, and why it matters. Cross-link related terms
  with `/glossary/<slug>` links.
- No em dashes.
