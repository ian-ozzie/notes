---
title: video
focus:
type: command
tags: []
created: 2025-09-09
updated: 2026-01-01
archived: false
---

# Video tasks

## Tasks

### for-web

Inputs: INPUT, OUTPUT

Environment: OUTPUT=

```bash
if [ -z "${OUTPUT}" ]; then
    prefix=${INPUT%.*} 
    extension=${INPUT##*.}
    OUTPUT=${prefix}-for-web.$extension
fi

ffmpeg -i $INPUT -c:v libx264 -crf 23 -preset medium -c:a aac -b:a 128k $OUTPUT
```
