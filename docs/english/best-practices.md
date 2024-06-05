---
description: Curio best practices
---

# Best Practices

1. All miner IDs should be part of the base layer. We highly recommend not creating separate layers for different MinerIDs but using different layers for control addresses if required.
2. No worker should be dedicated to specific minerIDs. All Curio nodes should be setup to allow jobs for any minerIDs.
3. Multiple workers should be started with `--post` layer to allow fast wdPost and winPost turn around time.&#x20;
