# Guardian Nexus — v0.1 Specification

Guardian Nexus is an on-prem, BYOS (Bring Your Own Storage) inspection data backbone
designed for NDE, quality, and compliance environments.

This repository contains **specifications only**.
No production code lives here.

---

## Scope (v0.1)

v0.1 defines the **foundational data backbone** required to:

- Ingest large inspection files
- Enforce metadata and naming standards
- Normalize storage without moving customer data
- Support future search, audit, and intelligence layers

v0.1 is intentionally minimal and infrastructure-focused.

---

## Non-Goals (v0.1)

The following are explicitly **out of scope**:

- AI/ML analysis
- Visualization dashboards
- Client portals
- Cloud hosting
- Automated defect interpretation

These are planned for later phases.

---

## Deployment Philosophy

- Fully on-prem
- Client-owned storage (NAS / SAN / local)
- No cloud dependency
- ITAR-capable
- Web-based UI served inside client network

---

## Roadmap (High-Level)

- v0.1 — Data backbone & schema enforcement
- v0.2 — Migration, search, audit readiness
- v1.0 — Enterprise-ready inspection intelligence

---

## Status

Active specification.
Implementation in progress.
