---
title: image
focus:
type: command
tags: []
created: 2025-09-02
updated: 2026-01-01
archived: false
---

# Image tasks

## Tasks

### png-optimise

Inputs: FILES

```
nix run nixpkgs#oxipng -- "$@"
```

### png-optimise-max

Inputs: FILES

```
nix run nixpkgs#oxipng -- -opt max --fast --zopfli "$@"
```
