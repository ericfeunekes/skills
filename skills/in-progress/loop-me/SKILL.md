---
name: loop-me
description: Grill me about specs for the workflows I want to build, within this workspace.
disable-model-invocation: true
argument-hint: "A workflow to design, or nothing to go find one"
---

Run a stateful session using the `grilling` skill whose only output is **workflow** specs. Use the grilling discipline (relentless, a round of questions at a time, a recommended answer attached to each) aimed at the vocabulary and goal below. Before writing, inspect the workspace's existing workflow, specification, and vocabulary conventions and use their owning surfaces. If the workspace has no established home, agree one with the user before the first write. Create, edit, and delete specs there as the grilling resolves things.

## The loop lens

A **loop** is a recurring pattern: a process, a repeated decision, a recurring event, or a scheduled activity. Use loops as a discovery lens when repetition helps reveal work worth specifying, and propose consequential loops the user may not have noticed.

A **workflow** is the spec of one loop, made real. You run a workflow on a loop: the loop is its running instantiation. Keep one source-of-truth specification for each workflow in the surface established by the workspace and user.

## Vocabulary

A shared language, reached for only when a workflow calls for it: never a checklist. **Mandate nothing structural**: a workflow needs no AI, no checkpoint, and no schedule unless the grilling shows it does.

- **Trigger**: what fires each run, an **event** (a new email, a new issue) or a **schedule** (every morning). Event-triggering is usually the more efficient.
- **Checkpoint**: a human-in-the-loop point where the user is asked to verify or decide. Some workflows have none and run autonomously; some use no AI at all.
- **Checkpoint placement**: do useful preparation before involving the human while authority, risk, reversibility, and review cost support it. Place the checkpoint where the human still has a meaningful choice.
- **Brief**: what a checkpoint presents, a decision-ready summary of what was produced, why it matters, and where the underlying material lives. Match the detail to what the decision requires.

## Definition of done

A workflow spec is done when an implementer agent could build it without asking a single question. Grill until then; nothing is done while a question remains.

## The workspace

Use the workspace's existing sources for workflow specifications, working context, and vocabulary. When no convention exists, agree the smallest durable arrangement that lets an implementer find the workflow and its governing context later.
