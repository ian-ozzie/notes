---
title: tls
focus:
type: command
tags: []
created: 2026-01-01
updated: 2026-01-01
archived: false
---

# TLS Tasks

## tasks

### check-expiry

Inputs: HOSTNAME, PORT

Environment: PORT=

```bash
if [ -z "${PORT}" ]; then
    PORT=443
fi

openssl s_client -showcerts -servername $HOSTNAME -connect $HOSTNAME:$PORT | openssl x509 -noout -dates
```
