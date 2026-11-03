# Data models

AquaGuard publishes four NGSI-LD entity types for flood resilience. They are documented and validated in the [code repository](https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/smart-data-models). Pydantic schemas live in `storage/broker/schemas/`, with the rules described in [validation-rules.md](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/smart-data-models/validation-rules.md).

| Type | Role |
| --- | --- |
| [WeatherObserved](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/smart-data-models/WeatherObserved.md) | ECMWF precipitation and meteorology forecasts |
| [SoilMoistureObserved](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/smart-data-models/SoilMoistureObserved.md) | Sentinel-1 soil saturation |
| [FloodRiskObserved](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/smart-data-models/FloodRiskObserved.md) | Flood-risk class and municipal alerts |
| [PointOfInterest](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/smart-data-models/PointOfInterest.md) | Settlements, drainage, and retention assets |

`WaterLevelObserved` is deferred. The pilot is built on satellite and forecast data, so a water-level sensor type is not part of the current models.

The model files are part of the Apache-2.0 code repository. The description on this page is CC BY 4.0, with the rest of this pilot repository’s documentation.
