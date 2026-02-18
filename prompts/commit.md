---
name: "commit"
title: "Commit Changes"
description: "Commit with conventional commit format"
arguments:
  - name: "instructions"
    description: "Additional instructions about the commit message"
    default: ""
examples:
  - "@commit"
  - "@commit feat"
---

Commit with conventional commit format.
MUST NOT create new git repositories. Abort if no git repository exists.
Never use `--no-verify` flag unless user explicitly asks for it.
Additional instructions that should be included in the commit message: {instructions}
