---
name: "sync"
title: "Sync Content"
description: "Re-read and refresh AI memory with current content from files or directories"
arguments:
  - name: "target"
    description: "File path, directory path, or content to re-read and sync"
  - name: "then"
    description: "What to do after the sync. Default: nothing to do"
    default: ""
examples:
  - "@sync file.py" # sync one file
  - "@sync file_1.py,file2.py" # sync multi files
  - "@sync file_1.py 'add more comments'" # sync then edit
---

Re-read and refresh your memory with the current content from: {target}
The content has been modified since you last accessed it.
{then}
