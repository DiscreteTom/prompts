---
name: "explore"
title: "Explore"
description: "Explore and understand code, systems, or concepts"
arguments:
  - name: "scope"
    description: "Scope of exploration (e.g., current project, specific module, system). Default: current project"
    default: "current project"
examples:
  - "@explore" # explore current project
  - "@explore 'how the auth system is implemented'" # explore specific feature
---

Explore and understand the code, system, or concept.
When searching using shell, prefer ripgrep (rg).
Exploration scope: {scope}
