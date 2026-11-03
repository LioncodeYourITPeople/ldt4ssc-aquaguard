# AquaGuard

AquaGuard is the LDT4SSC WS2 pilot for **flood resilience** in the municipalities of **Pangaion (Greece)** and **Limanu (Romania)**. It is a local digital twin that uses Copernicus Sentinel imagery, ECMWF weather forecasts, and open EU geospatial data to support early warning and planning scenarios, without local IoT sensor hardware.

This repository is the pilot’s public record: who is involved, what has been achieved since development started in July 2026, and where the reusable outputs live. The software itself is in the [AquaGuard code repository](https://github.com/LioncodeYourITPeople/aqua-guard).

- [`pilot.yaml`](pilot.yaml) — name, municipalities, consortium, and contacts.
- [`updates/`](updates/) — the chronological progress record (milestones, lessons, and assets).
- [Code repository](https://github.com/LioncodeYourITPeople/aqua-guard) — platform, models, and technical documentation.

## What this repository is for

This repository is the **project repository** for this pilot within LDT4SSC. It exists so that:

- The pilot has a **single canonical public location** for its work that is visible to the LDT4SSC community and to the wider public.
- The pilot’s **updates, milestones, lessons learned, and shared assets** can be published in a structured form and aggregated by the Knowledge Hub and the LDT4SSC project website.
- The pilot **owns its own record** of its work, independently of any central project infrastructure. If LDT4SSC project infrastructure evolves or ends, the content in this repository remains intact, open, and accessible.
- Outputs produced by the pilot can be **preserved, cited, and reused** by others, now and in the future.

This repository is **the pilot’s own**. The consortium maintains the template and the aggregation infrastructure, but the content is owned, authored, and controlled by the pilot.

This repository was created from the [LDT4SSC pilot template](https://github.com/ldt4ssc/pilot-template) and follows the structure and conventions of the LDT4SSC pilot documentation framework.

## Repository structure

- [`pilot.yaml`](pilot.yaml) — core metadata describing this pilot (name, partners, work strand, focus areas).
- [`updates/`](updates/) — structured updates on the pilot’s journey: milestones, lessons learned, general progress, and references to assets. See [`updates/README.md`](updates/README.md) for the format.
- [`docs/`](docs/) — a short index of the platform, with links into the code repository’s technical documentation.
- [`assets/`](assets/) — descriptions of shared artefacts produced by this pilot.
- [`src/`](src/) — a pointer to the code repository. The implementation is maintained there.
- [`data-models/`](data-models/) — the NGSI-LD flood entity types and links to their schemas.

## Licensing

Code in this repository is licensed under the Apache License 2.0. Content and documentation are licensed under Creative Commons Attribution 4.0 International (CC BY 4.0) unless stated otherwise. See [`LICENSE`](LICENSE) for details.

The AquaGuard platform in the code repository is licensed under the Apache License 2.0.

## About LDT4SSC

LDT4SSC (Local Digital Twins for Smart and Sustainable Communities) is a project funded by the Digital Europe Programme under grant agreement number 101226211, developing an interconnected ecosystem of Local Digital Twins across Europe.

Learn more at the [LDT4SSC project website](https://ldt4ssc.eu/) and the [LDT4SSC Knowledge Hub](https://knowledgehub.ldt4ssc.eu/).
