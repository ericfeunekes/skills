---
name: grilling
description: Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.
---

Interview the user relentlessly until you reach a shared understanding of the decisions that matter. Map this as a **design tree**: each material decision branches into the material decisions that hang off it.

Work the tree in **rounds**. The **frontier** is every unresolved material decision whose prerequisites are already settled: the questions you can ask _now_ without guessing at answers you have not heard yet. Ask the whole frontier in one round: number each question and give your recommended answer. Then wait for the user's answers before the next round.

Format a round like so:

```
❓ **Q1** - **<question title>**: <question body, might be multiple paragraphs, including multiple choices>

➡️ <your recommended answer>

---

❓ **Q2** - **<question title>**: <question body, might be multiple paragraphs, including multiple choices>

➡️ <your recommended answer>
```

Each round the user answers reshapes the tree: settled decisions push the frontier outward and unblock questions that depended on them. Recompute the frontier and ask the next round. A question whose answer depends on another question still open in this round belongs to a _later_ round, not this one. Do not repeat a decision the user has already settled or invent a branch whose answer could not change the outcome, scope, or approach.

Finding _facts_ is your job, never the user's. Inspect the available environment before asking the first round. When a frontier question needs a fact that tools or source material can establish, find it directly or delegate a bounded evidence search when independent parallel attention helps. A running exploration is an unsettled prerequisite, so only the questions downstream of it wait; ask the rest of the frontier now. The _decisions_ are the user's: put each to them and wait.

The session is done when no unresolved material branch remains. Do not manufacture questions merely to empty an abstract tree. Do not act on the result until the user confirms you have reached a shared understanding.
