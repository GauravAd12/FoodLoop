# FoodLoop — Deployment Comparison Research

A sample food waste management web application for evaluating **traditional Ubuntu VM deployment versus Docker/Kubernetes cloud-native deployment** as part of the COMP607 Production Project.

**Current status:** Worktribe ethics application is submitted and **awaiting approval**. The development prototype has been prepared locally but its source code has not been published to this repository. Follow university approval requirements before assessed product development or experiments.

See [Project Roadmap](docs/ROADMAP.md) for architecture, deliverables, evaluation scenarios and WIP plans.

## Planned architecture
- FoodLoop browser interface and FastAPI API
- PostgreSQL 16 for both measured environments
- Traditional: Ubuntu, Nginx, systemd, SSH
- Cloud-native: Docker, Kubernetes, Terraform, GitHub Actions
- Measurements: release time, downtime, error rate, rollback, latency, resource use, cost and operator effort

Do not commit secrets, participant data or local databases.
