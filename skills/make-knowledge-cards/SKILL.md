---
name: make-knowledge-cards
description: Turn a user's pasted article or local Markdown/TXT file into a small set of focused, source-grounded knowledge cards. Use when the user wants important ideas distilled for learning or review.
---

# Make Knowledge Cards

Create 5–8 useful cards from the supplied article or local `.md`/`.txt` file. Follow the source language unless the user requests another language. Keep the cards understandable without adding unsupported facts.

## Method

1. Read the complete supplied text or supported local file. For files, use the available file-reading capability; do not fetch web pages or process PDFs.
2. Identify the article's central claims, concepts, processes, distinctions, and evidence. Rank them by importance to understanding or applying the article. Ignore incidental detail and repeated restatements.
3. Group only tightly related material. Give each card one independently explainable knowledge point; split a card if it teaches multiple takeaways.
4. Write one card per important point. Paraphrase accurately, preserve important qualifications and uncertainty, and do not add facts, causes, examples, or conclusions absent from the source. For opinion or argument pieces, make clear when a point is the author's claim; do not present it as independently established fact. Do not turn correlation into causation. A simple example may be created only to illustrate the stated idea; label it as an illustration, not as a source example.
5. Aim for 5–8 cards when the source supports that many distinct, useful points. Never pad, split artificially, or repeat content to reach a number. If fewer than five points are genuinely supported, return fewer and briefly say that the source did not support more. If the text is too fragmentary to derive reliable cards, explain what is missing and ask for a fuller source.
6. Check the final set for duplication, single-point focus, source fidelity, and whether each card has all required fields.

## Output

Use a numbered list. Each card must contain:

- **标题**: short and specific.
- **核心知识**: the main point in one sentence.
- **简明解释**: a plain-language explanation that adds clarity without merely repeating the core sentence.
- **例子或自测问题**: include a source-supported example when the article has one; otherwise ask a short question that can be answered from the card or source. Do not invent a purported source example.

Keep cards concise and self-contained. Add a brief note about limited source coverage only when that explains a set with fewer than five cards or a request for more material.

## Scope

Supported inputs are text pasted by the user and local Markdown or plain-text files. This skill does not fetch webpages, extract PDFs, create Anki decks, or provide a graphical interface. Do not silently substitute these workflows; explain the supported input needed when asked for an unsupported format.
