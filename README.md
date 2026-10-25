# OpsSignal — Early Warning & Operations Hub

[**Live dashboard**](https://udipta14.github.io/opssignal-early-warning-hub/) · Synthetic portfolio demo

OpsSignal illustrates an early-warning workflow for growth and operations teams: ingest events, validate data, detect drift against a baseline, prioritize by impact and confidence, then route evidence to a human for review.

## Dashboard views

- **Overview:** Workstream health, open signals, forecast deviation, review times, and recent activity.
- **Workflow map:** Ingest → Normalize → Validate → Detect drift → Prioritize → Human review. Select a stage to inspect what it consumes, checks, and passes forward.
- **Signal inbox:** Severity filters, confidence, estimated impact, evidence, and investigation suggestions.
- **Run history:** A traceable log of simulated cycles and outputs.
- **Data quality:** Guardrails and quarantined sample records.

## Run locally

Open index.html in a browser or serve this folder with any static file server. No dependencies, API keys, or external services are required.

## Safety boundary

All metrics, signals, and events are synthetic. The rules are illustrative, not production incident diagnosis. OpsSignal does not connect to customer systems, send messages, or perform write actions. Suggested next steps are for human review only.
