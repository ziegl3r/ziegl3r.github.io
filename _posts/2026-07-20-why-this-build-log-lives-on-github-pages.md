---
title: "Why This Build Log Lives on GitHub Pages"
hash: 4f9a2c1
tags: [meta, workflow]
---
First decision before writing a single post: where does this actually live?

I looked at Beehiiv and GitHub Pages side by side and it wasn't close for what I need.

<!--more-->

## What I needed

- Markdown-native, so writing here feels the same as writing a README
- Code-friendly, so snippets, commit logs, and screenshots from Claude Code sessions sit naturally in a post
- Zero cost, because this is a side project funding itself
- Full ownership of the content and the domain, no platform lock-in
- Something that fits the existing workflow: VS Code, git, Claude Code

## Why not Beehiiv

Beehiiv is a genuinely good newsletter tool, but it's built around an email-first editor, not a developer's toolchain. There's no git history, no local editing in VS Code, and no natural place for a commit log or a project write-up to live. It's the right tool for a mailing list — it's the wrong tool for a portfolio.

## Why GitHub Pages

GitHub Pages won on every point that mattered:

- Every post is a markdown file in a repo I already own
- Jekyll builds it automatically on push — no separate hosting bill, no build pipeline to babysit
- Commit history *is* the build log. For something like the CCA-F certification, where the goal is proving hands-on skill, a documented history of real commits is stronger evidence than a badge on its own.

Beehiiv isn't off the table forever — it's a reasonable email layer to bolt on later if this grows an audience worth emailing. But the writing surface, the canonical one everything else points back to, is this repo.
