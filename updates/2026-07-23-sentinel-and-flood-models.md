---
schema_version: 1
type: milestone
date: 2026-07-23
title: "Sentinel pipeline and the first flood-risk models are in place"
tags:
  - sentinel
  - machine-learning
  - flood-risk
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/ml"
  - "https://github.com/LioncodeYourITPeople/aqua-guard/tree/main/docs/ingestion"
---

The flood data path is running end to end in the development stack.

A satellite inventory covers the two pilot areas, and the Sentinel pipeline ingests soil-moisture inputs. A convolutional model estimates soil saturation from those inputs. A LightGBM classifier turns precipitation, soil moisture, and local covariates into a flood-risk class. Architecture notes in the code repository describe how ingestion, the context broker, and the models fit together.

Municipal staff can work from satellite and forecast data, with a person still confirming any alert before it goes out.
