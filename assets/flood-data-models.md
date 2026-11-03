# Flood NGSI-LD data models

Four entity types that carry AquaGuard’s flood picture on an NGSI-LD context broker.

## Purpose

Give another municipality a documented, validated set of entities for forecasts, soil saturation, flood risk, and the places those risks refer to.

## What it contains

| Type | Role |
| --- | --- |
| WeatherObserved | ECMWF precipitation and meteorology forecasts |
| SoilMoistureObserved | Sentinel-1 soil saturation |
| FloodRiskObserved | Flood-risk class and municipal alerts |
| PointOfInterest | Settlements, drainage, and retention assets |

Field-level descriptions and validation rules are in the code repository. A short index is in [`data-models/README.md`](../data-models/README.md).

## Licence

The schemas and model documents are part of the Apache-2.0 code repository. This description is CC BY 4.0.

## Location

[docs/smart-data-models](https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/smart-data-models)

## Status

Core types used by the running pipelines and the dashboard. `WaterLevelObserved` is documented as deferred because the pilot does not depend on water-level sensors.
