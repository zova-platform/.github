<p align="center">
  <img src="https://raw.githubusercontent.com/zova-platform/docs/main/branding/logo.png" alt="ZOVA logo" width="120" />
</p>

<h1 align="center">ZOVA</h1>
<p align="center"><b>MOVE YOUR WAY.</b></p>

<p align="center">
  A Grab-style ride-hailing platform built as Go microservices —<br />
  real-time driver tracking, dispatch, trip lifecycle and full observability.
</p>

---

### What it does

Riders request a car or motorcycle, the system finds the nearest available driver,
offers the job, and both sides follow the trip live on a map until drop-off.
Food delivery is planned on top of the same dispatch engine.

### Tech

**Backend:** Go · gRPC · NATS JetStream · PostgreSQL + PostGIS · Redis · OSRM
**Frontend:** React · TypeScript · Vite · MapLibre
**Ops:** Docker · GitHub Actions · OpenTelemetry · Prometheus · Grafana · k3s

### Status

| Phase | Scope | Status |
| --- | --- | --- |
| 0 | Foundation: CI, shared libraries, local stack | 🚧 In progress |
| 1 | Ride MVP: request → match → trip → complete | ⏳ Planned |
| 2 | Real-time map and driver simulator | ⏳ Planned |
| 3 | Reliability and automated deploy | ⏳ Planned |
| 4 | Payments and Kubernetes | ⏳ Planned |
| 5 | ZOVA Food | ⏳ Planned |

### Start here

- 📐 [Architecture overview](https://github.com/zova-platform/docs/blob/main/architecture/overview.md)
- 📦 [Repository specs](https://github.com/zova-platform/docs/blob/main/repos.md)
- 🗺️ [Plan](https://github.com/zova-platform/docs/blob/main/plan.md)
- 🧭 [Architecture decisions](https://github.com/zova-platform/docs/tree/main/adr)

### Repositories

| Repo | Purpose |
| --- | --- |
| [docs](https://github.com/zova-platform/docs) | Architecture, ADRs, branding, benchmarks |
| [proto](https://github.com/zova-platform/proto) | gRPC contracts for every service |
| [platform-go](https://github.com/zova-platform/platform-go) | Shared Go infrastructure library |
| [ci-workflows](https://github.com/zova-platform/ci-workflows) | Reusable GitHub Actions workflows |
| [deploy](https://github.com/zova-platform/deploy) | Docker Compose and Kubernetes manifests |
| [service-template](https://github.com/zova-platform/service-template) | Template for new Go services |

<sub>Personal learning project. Map data © OpenStreetMap contributors.</sub>
