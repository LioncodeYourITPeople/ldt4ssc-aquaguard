---
schema_version: 1
type: milestone
date: 2026-08-27
title: "Alerts and background jobs follow the latest v2 contract"
tags:
  - early-warning
  - interoperability
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/jobs"
---

Flood alerts are part of the platform again, on a dedicated page, and they follow the latest twin-manager v2 contract.

Background work — training, inference, and other long tasks — runs through the jobs module shared with our other twin. The queue, result files, and the contract payloads were brought across together, so a job started from the dashboard finishes under the same rules the manager already uses.
