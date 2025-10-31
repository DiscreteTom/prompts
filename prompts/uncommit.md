---
name: "uncommit"
title: "Undo Last Commit"
description: "Undo last git commit while preserving all changes"
examples:
  - "@uncommit"
---

Undo last commit using `git reset HEAD^ --soft`. This keeps all changes staged.
Never run `git commit` without explicit permission.
