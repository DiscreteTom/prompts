---
name: "commit_staged"
title: "Commit Staged Only Changes"
description: "Commit staged only changes to git using conventional commit format"
arguments:
  - name: "instructions"
    description: "Additional instructions about the commit message (e.g. feat, #12, Co-authored-by: name). Default: no additional instructions"
    default: ""
examples:
  - "@commit_staged" # commit with auto generated commit message
  - "@commit_staged feat" # specify commit type
  - "@commit_staged feat(web)" # specify commit type and scope
  - "@commit_staged 'feat(web) #12'" # specify related resources
---

Commit staged only changes to git using conventional commit format.
You should use `git diff --cached` to see all the staged changes.
Additional instructions that should be included in the commit message: {instructions}
