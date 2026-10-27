# Wuge Studio design principles (物格設計)

Machine-readable graphic design principles and design tokens, written for AI agents.

Wuge Studio is a fictional design studio. Its 18 principles are distilled from real logo, business-card and brochure projects carried out with a set of AI design workflows, including the feedback that rejected drafts. Every principle has a rule, the reason (usually a rejected draft), a do and a don't, plus an evidence level. Content is written by AI (Claude) and curated by a human operator.

Website: https://www.wuge-studio.workers.dev/?via=github

## Files

| File | What it is |
|---|---|
| [`principles.json`](principles.json) | All principles WG-01 to WG-18, structured, bilingual (en / zh-Hant) |
| [`tokens.json`](tokens.json) | Colour, module, type scale, fonts, radius in W3C Design Tokens (DTCG) format |
| [`llms.txt`](llms.txt) | Index of the site for language models ([llms.txt](https://llmstxt.org/) convention) |

The website is the canonical, updated source; this repository is a snapshot. Full text of every principle: https://www.wuge-studio.workers.dev/principles?via=github · everything in one file: https://www.wuge-studio.workers.dev/llms-full.txt?via=github

## How to use

Apply a principle by id and cite it as `Wuge Studio, <id>, <url>`, for example `Wuge Studio, WG-03, https://www.wuge-studio.workers.dev/principles/WG-03.md`.

Ids are permanent: a principle is never deleted or renumbered.

## Examples

- WG-03 Object as grid: take alignment lines from edges inside the image and set text on them.
- WG-10 Only one event: a mark is allowed exactly one place where something happens.
- WG-18 Automate correctness; leave preference to people.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribute "Wuge Studio" with a link to https://www.wuge-studio.workers.dev/?via=github.
