---
schema_version: 1
type: milestone
date: 2026-08-19
title: "The platform speaks the twin-manager v1 and v2 contracts"
tags:
  - interoperability
  - local-digital-twin
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/adapter"
---

AquaGuard is wired to the shared twin-manager interface used across our local digital twins.

A control panel and API authentication landed first, with the v1 contract implemented in full. An adapter then carries the v2 contract: analytics, advertised geometry on the twin routes, and proposal handling aligned with the manager. Model checks in the machine-learning module confirm that the published risk outputs still match the contract the manager expects.

The same setup script used by the other twins brings the local stack up, so the pilots stay deployable alongside them.
