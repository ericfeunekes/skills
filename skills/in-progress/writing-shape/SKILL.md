---
name: writing-shape
description: "Writing, exploit: shape raw material into a coherent piece, chunk by chunk."
disable-model-invocation: true
---

<what-to-do>

The user has passed (or will pass) a markdown file of raw material. Treat it as the input pile: anything from a tidy list of fragments to a wall of unstructured prose to a transcript. The format does not matter. Read it end-to-end before doing anything else.

Then run a shaping session that produces a separate draft. This is **exploit**: the exploring is done, the pile is fixed, so commit to a structure and mine the pile to fill it. Do not edit the raw material file: it is read-only to this skill.

If the user did not say where to save the draft, ask once and remember the path.

</what-to-do>

<supporting-info>

## The loop

1. **Read the pile.** Read the input file in full. Form a sense of what's in it.
2. **Establish the audience footing.** Settle what the audience knows walking in, what the opening may signpost for later explanation, and what the piece must establish before relying on it. See [Audience footing](#audience-footing).
3. **Settle the opening.** When the frame is unresolved, draft 2 or 3 candidate openings that imply genuinely different theses or angles and have the user choose or combine them. When the frame is already settled, use it rather than manufacturing alternatives.
4. **Grow chunk by chunk.** After the opening lands, ask "given this opening, what does the audience need next?" Pull material from the pile to answer. A **chunk** is a coherent unit that advances understanding: a paragraph group, section, slide, slide sequence, list, table, diagram, quote, or code example. Choose its form deliberately. Ask for user approval at meaningful structural choices instead of requiring approval for every paragraph.
5. **Write each agreed chunk.** Add the chunk when it is settled so the user can see the piece taking shape. Re-read the draft before each write and preserve the user's intervening edits.
6. **Loop step 4 until the piece is done.** The user decides when it is done.

## Audience footing

The audience must have enough footing to follow every consequential move. The unit is the concept, not the word for it: a chunk can rely on an idea the audience lacks even with no jargon in sight. Where a concept has a name (a **term**), land the idea and term together when the distinction matters.

A concept reaches the audience in one of three ways:

- **Prerequisite**: the audience brings it. Establish this at the start.
- **Introduced**: a chunk establishes it before later reasoning relies on it.
- **Signposted**: an early overview names the concept or conclusion and clearly promises the explanation that follows. The audience can carry the signpost, but later reasoning cannot rely on details that have not yet been established.

Keep a running sense of the audience's footing. When the next move requires a missing foundation, establish it first or restructure the move. An executive overview or impact-first opening may signpost conclusions before the body develops them, provided the sequence makes that promise clear.

The lever is what the audience brings, what the piece introduces, and what it signposts. Demand too much up front and you shut readers out; explain too much in the opening and the point disappears.

## Conversational feel

This is a grilling session inverted. In ideation, the question was "what are you actually noticing?" Here it is "what is this piece actually doing, and in what order does the audience need to receive it?" Push back. Refuse to let weak transitions slide. If a chunk does not earn its place, cut it.

Specific moves to keep using:

- "What does this chunk do for the audience that the previous one didn't?"
- "If I cut this, what breaks?"
- "Is this prose, or should it be a list? Why prose?"
- "This chunk is doing two jobs: split it or pick one."
- "The opening promised X. We've drifted to Y. Either re-thread it or change the opening."

## Pulling from the pile

Treat the raw material as a quarry, not a script. Pull a fragment, rework it to fit the surrounding chunk, and place it. A fragment may be split, merged with another, or paraphrased. The pile's job is to be mined; the finished piece's job is to feel coherent.

If the pile lacks something the piece needs, name the gap explicitly: "We need an example here and the pile doesn't have one. Give me one now or we cut this section."

## Format arguments to actually have

When choosing how to render a chunk, weigh these tradeoffs out loud with the user, not silently:

- **Prose vs. list.** Prose carries argument; lists carry parallel items. If items aren't truly parallel, prose is better. If they are, a list is faster to scan.
- **Table vs. repeated structure.** If the same shape repeats 3+ times with the same fields, a table. Otherwise prose with bold leads.
- **Quote vs. paraphrase.** Quote when the original wording is the point. Paraphrase when only the idea matters.
- **Code block vs. inline code.** Multi-line, runnable, or illustrative → block. Single token or identifier → inline.
- **Narrative vs. visual form.** Use a table, diagram, slide, or slide sequence when spatial arrangement or comparison carries meaning better than prose. In a visual medium, decide what belongs together, the order, and the rough content relationship. Leave final typography, template selection, and artifact rendering to the medium's production workflow.

## Writing rhythm

Write to the draft as each chunk is agreed. Re-read the file from disk before every write: the user may have edited between turns. Never overwrite blindly. If the user wants a chunk rewritten, edit that chunk in place and leave the rest alone.

## Out of scope

- Mining for new fragments that aren't in the pile (handle gaps as in "Pulling from the pile").
- Editing the raw material file.
- Publishing, formatting for a specific platform, or adding frontmatter the user didn't ask for.

</supporting-info>
