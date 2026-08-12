---
title: "Three Modes of Human-AI Collaboration: Automation, Augmentation, Agency"
hash: c2d9f44
tags: [cca-f, study-notes]
---
The second framework from the AI Fluency Foundations course sorts every task into one of three collaboration modes. The useful part isn't the definitions — it's using them to decide how to approach a task *before* starting it.

<!--more-->

## The three modes

- **Automation** — Claude runs the task end-to-end with little to no human input mid-stream. Best fit when the task is well-defined, low-stakes if wrong, and easy to check afterward.
- **Augmentation** — Claude and I go back and forth. I stay in the loop the whole way, steering and correcting. Best fit for anything where my judgment adds real value along the way, not just at the end.
- **Agency** — Claude operates with real autonomy toward a goal, making its own intermediate decisions. Best fit when the task is complex enough that specifying every step up front isn't realistic, and I trust the checkpoints in place to catch problems.

## Picking a mode on purpose

Before this, I was picking a mode by instinct — mostly augmentation, out of habit. The framework's actual point is that the choice should follow from the task: how well-defined it is, how expensive a mistake would be, and how easy the output is to verify. A boilerplate config file is automation. A tricky architecture decision is augmentation. A long multi-file refactor with tests as a safety net starts to look like agency.

Next up: applying all three modes to a real CarTechTutor build and writing up which one actually worked best for each stage.
