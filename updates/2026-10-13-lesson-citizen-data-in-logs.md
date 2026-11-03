---
schema_version: 1
type: lesson
date: 2026-10-13
title: "Citizen contact details stay out of operational logs"
tags:
  - privacy
  - early-warning
work_strand: WS2
authors:
  - name: "Konstantinos Despoinidis"
    organisation: "LIONCODE PC"
related_assets:
  - "https://github.com/LioncodeYourITPeople/aqua-guard/blob/main/docs/user-manuals/en/data-and-privacy.md"
---

Early warning needs a phone number or an email address. Those values are easy to copy into a pipeline log, a job result, or a broker payload while debugging delivery.

## What we changed

Contact details live in the citizen registry and in the notification dispatch. Saturation maps, risk entities, and application logs carry the flood signal and the decision, and they leave the contact itself out. Account deletion and the retention jobs can then remove the person without hunting through log files.

## What we are taking forward

Any new alert path is checked for the same split before it is merged: the message may say who approved the send, and the log may say that a send happened. The address it was sent to stays in the contact store.
