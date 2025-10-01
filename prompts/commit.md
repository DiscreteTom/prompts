---
name: "commit"
title: "Commit Changes"
description: "Commit changes to git using conventional commit format"
arguments:
  - name: "type"
    description: "Commit type (e.g., feat, fix, docs, refactor). Default: infer from changes"
    default: "infer from changes"
  - name: "scope"
    description: "Scope of the commit (e.g., api, ui, docs). Default: no scope"
    default: ""
  - name: "suffix"
    description: "Text to append at the end of commit message (e.g. #12, Co-authored-by: name). Default: no suffix"
    default: ""
---

Commit changes to git using conventional commit format.

- type: {type}
- scope (if provided): {scope}
- append this suffix to the commit message (if provided): {suffix}
