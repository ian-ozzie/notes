---
title: password
focus:
type: command
tags: []
created: 2025-07-15
updated: 2026-01-01
archived: false
---

# Password tasks

## Tasks

### random

Inputs: LENGTH

Environment: LENGTH=32

```
nix run nixpkgs#pwgen -- --capitalize --numerals --symbols --ambiguous -1 $LENGTH 10
```

### words

Inputs: WORDS

Environment: WORDS=5

```
nix run nixpkgs#xkcdpass -- --delimiter '-' --case alternating --numwords $WORDS --count 10
```
