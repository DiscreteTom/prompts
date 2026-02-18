---
name: "commit-staged"
title: "Commit Staged Only Changes"
description: "Commit staged only changes to git using conventional commit format"
arguments:
  - name: "instructions"
    description: "Additional instructions about the commit message (e.g. feat, #12, Co-authored-by: name). Default: no additional instructions"
    default: ""
examples:
  - "@commit-staged" # commit with auto generated commit message
  - "@commit-staged feat" # specify commit type
  - "@commit-staged feat(web)" # specify commit type and scope
  - "@commit-staged 'feat(web) #12'" # specify related resources
---

Commit staged only changes to git using conventional commit format.
You should use `git diff --cached` to see all the staged changes.
Never use `--no-verify` flag unless user explicitly asks for it.
Additional instructions that should be included in the commit message: {instructions}
