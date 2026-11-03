---
schema_version: 1
type: asset
date: 2026-10-16
title: "Flood platform and NGSI-LD models available for reuse"
tags:
  - data-models
  - interoperability
  - flood-resilience
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard"
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/smart-data-models"
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/user-manuals"
---

The AquaGuard platform and its flood data models are available from the code repository while the LDT4SSC Assets and Services Repository is still being opened for submissions.

## What is included

The platform covers ingestion, an NGSI-LD context broker, flood-risk models, what-if scenarios, a dashboard, and citizen alerts. Code is under the Apache License 2.0.

Four entity types carry the flood picture: WeatherObserved for forecasts, SoilMoistureObserved for satellite soil saturation, FloodRiskObserved for risk classes and alerts, and PointOfInterest for settlements and drainage or retention assets. Schemas and validation rules sit next to the models in the repository. Descriptions published in this pilot repository are under CC BY 4.0.

User manuals in English, Greek, and Romanian explain the map, scenarios, privacy, and how the models are used.

## What comes next

These outputs will move into the Assets and Services Repository when that submission path opens. Until then, the links above are the canonical copies, and short descriptions live in the `assets/` folder of this repository.
