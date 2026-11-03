---
schema_version: 1
type: milestone
date: 2026-07-27
title: "Analysis-ready satellite and terrain layers feed the models"
tags:
  - sentinel
  - geospatial
  - data-integration
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/ingestion"
---

The models now train and score on analysis-ready data for both pilots.

Sentinel-1 and Sentinel-2 products are gridded for the areas of interest, including an NDMI layer. Static layers add a digital elevation model, slope, Corine land cover, and drainage. Dataset versions record which inputs a training run used. The map draws roads from OpenStreetMap, and the earlier sample datasets have been taken out of the live paths.

Backfill and publishing were tightened in the same stretch so repeated runs upsert existing records and soil saturation stays on a consistent scale.
