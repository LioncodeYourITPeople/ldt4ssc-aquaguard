# Documentation

AquaGuard’s technical documentation lives with the code. This page is the index for the pilot record. Follow the links into the [code repository](https://github.com/LioncodeYourITPeople/aqua-guard) for the full guides.

The platform is a flood-resilience local digital twin for Pangaion and Limanu. Satellite and weather data are ingested, published as NGSI-LD entities, scored by flood-risk models, and shown to municipal staff. A person approves any citizen alert before it is sent.

| Area | What it covers | Where to read it |
| --- | --- | --- |
| Ingestion | ECMWF / Open-Meteo forecasts, Sentinel-1 and Sentinel-2, and static terrain layers | [Ingestion](https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/ingestion) |
| Context broker | NGSI-LD entities in Scorpio, including subscriptions | [Services](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/platform/Services.md) |
| Flood models | Soil-saturation CNN, LightGBM risk classifier, and the training dataset | [Machine learning](https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/ml) |
| What-if | Retention and drainage scenarios drawn on the map | [What-if](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/ml/WhatIf.md) |
| Dashboard | Map, scenarios, alerts, and the citizen view, in English, Greek, and Romanian | [User manuals](https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/user-manuals) |
| Citizen alerts | Registration, human approval, and delivery | [Data and privacy](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/user-manuals/en/data-and-privacy.md) |
| Interoperability | MIM0 and MIM2 working log | [MIMs compliance](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/platform/MIMs-Compliance.md) |

The grant-style description of the two services (early warning and what-if planning) is in [Description.md](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/Description.md) in the code repository.

Progress over time is recorded in [`updates/`](../updates/), not in this folder.
