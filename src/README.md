# Source code

AquaGuard’s implementation is maintained in the [code repository](https://github.com/LioncodeYourITPeople/aqua-guard). This folder points there. The platform is licensed under the Apache License 2.0.

| Area | Role |
| --- | --- |
| `dashboard` | Web interface for staff and citizens (English, Greek, Romanian) |
| `rest` | HTTP API, including alerts, proposals, and citizen contacts |
| `ml` | Soil-saturation CNN, LightGBM flood-risk classifier, and what-if scoring |
| `storage` | Postgres, Garage object storage, NGSI-LD broker schemas, and pipelines |
| `sources` | External data access used by the pipelines |
| `adapter` | Twin-manager v2 contract |
| `jobs` | Background queue for training, inference, and other long tasks |
| `auth` | Keycloak realms, roles, and optional admin MFA |
| `catalog` | DCAT-AP catalogue metadata |

Local setup, ports, and Make targets are documented in [Services](https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/platform/Services.md).
