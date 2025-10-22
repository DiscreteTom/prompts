---
name: "commit"
title: "Commit All Changes"
description: "Commit all changes to git using conventional commit format"
arguments:
  - name: "instructions"
    description: "Additional instructions about the commit message (e.g. feat, #12, Co-authored-by: name). Default: no additional instructions"
    default: ""
examples:
  - "@commit" # commit with auto generated commit message
  - "@commit feat" # specify commit type
  - "@commit feat(web)" # specify commit type and scope
  - "@commit 'feat(web) #12'" # specify related resources
---

Commit changes to git using conventional commit format.
You should use `git diff HEAD` to see all the staged and unstaged changes.
Additional instructions that should be included in the commit message: {instructions}
