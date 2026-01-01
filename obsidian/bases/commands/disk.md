---
title: disk
focus:
type: command
tags: []
created: 2025-07-15
updated: 2026-01-01
archived: false
---

# Disk tasks

## Tasks

### image

Inputs: INPUT, OUTPUT

```
dd if=$INPUT of=$OUTPUT bs=4M status=progress
```

### mount

Inputs: DEVICE

```
udisksctl mount -b $DEVICE
```

### unmount

Inputs: DEVICE

```
udisksctl unmount -b $DEVICE
```
