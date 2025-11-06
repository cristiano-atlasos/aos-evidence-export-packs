[![latest tag](https://img.shields.io/github/v/release/cristiano-atlasos/aos-evidence-export-packs?label=latest%20tag)](https://github.com/cristiano-atlasos/aos-evidence-export-packs/releases)
[![license: MIT](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
**Quick links:** [NDJSON sample](./ndjson/sample_decision_trace.ndjson) • [OpenTelemetry JSON sample](./otel/decision_trace_example.json) • [release notes](https://github.com/cristiano-atlasos/aos-evidence-export-packs/releases)

# A/OS Evidence Export Packs
Minimal export examples for governed AI decisions — NDJSON (for SIEM/GRC bulk ingest) and OpenTelemetry JSON (for log pipelines).

## Contents
- `ndjson/sample_decision_trace.ndjson` — line-delimited DecisionTrace records
- `otel/decision_trace_example.json` — OpenTelemetry log-style record

Each record follows the A/OS DecisionTrace v0.1 draft.
