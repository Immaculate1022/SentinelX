# Sentinel X — Forensic Telemetry AI

**Escalate the signal, not the noise.**

Sentinel X is a forensic telemetry dashboard for autonomous incident analysis. It watches distributed login attempts, egress, latency, and sensor coverage in one control plane — and surfaces the evidence trail behind every anomaly instead of burying responders in raw alerts.

**Live deployment:** https://sentinelx-yr2kc2rd.manus.space/

## What it shows

- **Threat index** — a single rolling risk score across identity, edge, and workload sensors
- **Telemetry pressure map** — inbound pressure vs. outbound flow over a live window
- **Threat radar** — anomaly vectors scoped by identity and edge
- **Evidence trail** — retained events behind each escalation: anomaly clusters (e.g. auth failures at 4.6σ over baseline), sensor synchronization, policy window refreshes, privileged token observations
- **Scenario Lab** — inject a signal into a deterministic simulation; safe to replay

## In this repo

The production static build of the Sentinel X front end (`index.html` + `assets/`), snapshotted from the live deployment on 2026-10-04. Platform services behind the live site (session config, analytics) are not part of this snapshot; the live deployment above is the full experience.

## Lineage

Part of the same defensive-security body of work as [AHR-Endpoint](https://github.com/Immaculate1022/AHR-Endpoint) (Adaptive Hollow Reflector) — forensic visibility first, response timed to the signal.

## License

IOF Attribution License v1.0 — see [LICENSE](LICENSE).
