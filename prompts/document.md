---
name: "document"
title: "Update Documentation"
description: "Update README, examples, CHANGELOG and other related documentations"
arguments:
  - name: "focus"
    description: "Specific area or aspect to focus on when updating documentation"
    default: ""
examples:
  - "@document" # update all relevant documentation
  - "@document 'API changes'" # focus on API changes
---

Update README, examples, CHANGELOG and related documentation with only necessary changes.
Focus area: {focus}
