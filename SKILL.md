---
name: generate-jokes
description: Generate original jokes, punchlines, witty one-liners, humorous captions, light roasts, dad jokes, workplace-safe jokes, topic-based joke sets, or rewrites that make existing text funnier. Use when the user asks for jokes, funny lines, humor ideas, comedic punch-ups, humorous alternatives, or audience-specific comedy in any requested language or tone.
---

# Generate Jokes

## Core Approach

Create jokes that fit the user's topic, audience, language, and risk level. If the user gives little context, default to clean, broadly understandable jokes with clear setup and punchline.

Prefer original material over recycled jokes. Keep each joke concise unless the user asks for a story, monologue, sketch, or longer bit.

## Workflow

1. Identify the joke brief:
   - Topic or premise
   - Audience and setting
   - Language, dialect, or bilingual preference
   - Format: one-liner, setup-punchline, dad joke, caption, roast, pun, short bit, list, or rewrite
   - Tone: clean, dry, silly, clever, dark, sarcastic, wholesome, edgy, or absurd
   - Constraints: length, number of jokes, banned words, sensitive subjects, brand voice, age rating

2. Choose a comic engine:
   - Misdirection: lead the audience one way, then turn.
   - Incongruity: combine two frames that do not usually belong together.
   - Specificity: use concrete details instead of generic labels.
   - Escalation: build a pattern, then heighten it.
   - Wordplay: use ambiguity, homophones, idioms, or literal readings.
   - Reversal: flip status, expectation, cause and effect, or common advice.
   - Relatable truth: name a small, recognizable frustration.

3. Draft more candidates than requested when needed, then keep the strongest.

4. Polish the final set:
   - Put the funniest word or twist near the end.
   - Remove explanation unless the user asks for it.
   - Cut filler and throat-clearing.
   - Vary rhythm and structure across lists.
   - Avoid repeating the same premise with different wording.

## Safety And Taste

Keep humor aimed at situations, systems, language, objects, fictional characters, or willing participants. For roasts, keep them playful unless the user explicitly asks for sharper material and the target is appropriate.

Avoid punching down at protected classes, private individuals, trauma, disasters, self-harm, serious illness, or recent tragedies. When a requested target is risky, redirect the joke toward the situation, the speaker, a fictionalized version, or a harmless adjacent premise.

For workplace, classroom, public event, brand, or mixed-audience contexts, default to clean humor. For adult or edgy contexts, still preserve consent, specificity, and good taste.

## Language Handling

Write in the user's language by default. If the user asks in Chinese, produce Chinese jokes unless they request English or bilingual output. Preserve requested regional flavor when possible, but avoid forcing dialect, slang, or cultural references that may not land.

For translation or localization, do not translate wordplay literally if it breaks the joke. Rebuild the premise so the punchline works in the target language.

## Useful Output Patterns

For a simple request:

```text
Here are 5 clean jokes about remote work:
1. ...
```

For a punch-up request:

```text
Original:
...

Funnier options:
1. ...
2. ...
3. ...
```

For uncertain context:

```text
I will keep these clean and general. Here are...
```

Ask a brief clarifying question only when the missing detail changes the joke materially, such as audience age, public vs private setting, or whether a roast target consented.
