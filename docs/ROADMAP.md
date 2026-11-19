# FoodLoop — deployment comparison project roadmap

FoodLoop is the **sample web application**, not the principal research topic. The research remains a comparison of traditional Ubuntu VM deployment and cloud-native Docker/Kubernetes delivery, using one frozen application revision and repeatable experimental workloads.

## Application MVP
- Donor and receiver authentication
- Food listing CRUD, matching by location, pickup requests
- Notifications and basic analytics
- Same-origin browser interface and FastAPI API
- PostgreSQL 16 in both evaluated deployment environments
- Database migrations, liveness/readiness endpoints and automated tests

## Traditional deployment
Ubuntu VM, Python virtual environment, PostgreSQL, Nginx, systemd, SSH, scripted deploy/rollback.

## Cloud-native deployment
Docker, Kubernetes, Terraform, GitHub Actions, with Argo CD, progressive delivery, Prometheus/Grafana added based on MoSCoW priorities.

## Experiments
Use the **same application commit**, schema, data snapshot and test workload. Measure deployment duration, downtime, error rate, p95 latency, rollback/recovery, resource usage, rebuild time and operational effort. Repeat applicable release scenarios ten times per environment.

## Ethics and source control
Worktribe submission is **awaiting university approval**. Do not start formally assessed product implementation/testing or recruit participants until approval and supervisor confirmation. Use only synthetic data for demonstrations. Keep secrets, local databases and participant information out of Git.

## WIP presentation
Deadline: **30 November 2026, 12:00 midday**. Describe aims, literature, architecture, proposed experiments, design evidence, honest ethics status and remaining milestones. Never claim a deployment test that has not occurred.

## Deferred deliverables
The original Component 1 scope also includes a **deployment-control dashboard** with login, deploy, rollback, log viewing and monitoring. The FoodLoop sample application is distinct from that platform and does not replace it.
