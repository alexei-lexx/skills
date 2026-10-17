---
name: teach-me
description: "Teaches or recaps a topic in small ordered pieces, one at a time, basics to advanced. Use when the user asks to be taught, introduced to, walked through, refreshed on, or recapped on any topic, or wants it explained gradually instead of all at once."
---

# teach-me

Teach a topic one small piece at a time. Basics first, advanced later. Pause between pieces.

## Research

- Before planning, search for current info on the topic
- Don't rely only on built-in knowledge, which can be stale
- Favor authoritative sources (official docs, standards, blogs from recognized authorities) over random, unverified ones
- Check each source's date and prioritize recent sources

## Plan

Organize the topic into a series of items:

- For a recap, ask where to start, or start further in and back up if needed
- Break the topic into items that guide the user from basics to advanced
- An item is an explanation unit that covers exactly one idea, mechanism, rule, distinction, or pitfall (gotcha, edge case, inconsistency, trap)
- The last item is a summary: up to 5 bullets with only the most essential points
- Let the topic decide the item count (no fixed number)
- Use examples and evolve them across items where they make the topic clearer

Each item checklist:

- Item must build on earlier items, not later ones
- If an item refers to an earlier item, it must give again the necessary information from that item
- If an item leaves a detail for a later item, it must tell what that item will add
- Item must define topic-specific terms before their first use
- If an item is the first to use an example, the item must describe the example
- Item must cover one thing; move any extra into a new item
- Item must be written for a first-time reader who doesn't know the discussion around it
- If an item has code, and you can run that programming language, run it before sending and fix any error
- Item must be short: readable in about two minutes, roughly 300-400 words (that's a ceiling, not a target)

## Language

- Write all messages in ASD Simplified Technical English
- Avoid vague and filler phrases
- Write one sentence per bullet, with no period at the end
- Use blockquotes only for citations and speech
- Do not put quotation marks around blockquote text

## Deliver

- Start with a roadmap: item titles only, no explanations
- Then list the sources used in research
- Then deliver one item per message, using the item format below
- Wait for a clear go-ahead ("next", "continue", "go ahead") before sending the next item
- When the user's reply is anything besides a clear go-ahead — a question, a comment, or something off-topic — stay on this item and answer it
  - If the user asks about something a later item covers, name that item instead of going deeper
  - If the user asks for a fix, change only that part and don't rewrite the rest of the item
  - When fixing, remember future readers won't know the discussion and will see only the final version

## Adapt

If the user gets lost, or an item assumed something not yet covered:

1. Re-plan the remaining items: add one, reorder, or reword
2. Say in one line what changed and why
3. Resume with the corrected item once the user gives the go-ahead

Small wording tweaks need no announcement. Anything that changes what's coming next does.

## Format

Roadmap:

```
1. item title
2. item title
3. item title
...
```

Sources:

```
- source 1
- source 2
- source 3
...
```

Each item:

```
**N. Item title**

<one-line summary of what this item covers>

<explanation>

[N/TOTAL] Item title -> [N+1] Next item title
Say "next" or "go" when ready, or ask about this first.
```
