---
name: "bump"
title: "Bump Version"
description: "Bump current project to a new version"
arguments:
  - name: "version"
    description: "Target version, e.g. v1.1.1"
examples:
  - "@bump v1.1.1" # bump current project to v1.1.1
---

Bump current project to version: {version}
Update related files, including:

- CHANGELOG.md, create new h3 if needed, and update bottom link refs
- Project info file, e.g. pyproject.toml, package.json

You should also update lock files (e.g. uv.lock, package-lock.json)
using commands (e.g. `uv sync`) instead of modifying them directly.

You should also search (prefer ripgrep) for the old version
to see if there are other changes needed.

Don't commit after changes.
