<h1 align="center">Hi, I'm Minhyeok Seo 👋</h1>

<p align="center">
Systems & infrastructure-oriented developer building containerized services,
operational automation, and reliable backend workflows.
</p>

<p align="center">
Python · FastAPI · Docker · Docker Compose · Nginx · PostgreSQL · Redis
</p>

---

## About Me

I am a Computer Science student transitioning from backend systems development
toward infrastructure and cloud engineering.

I am interested in how systems run beyond application code:

- Containerized multi-service environments
- Scheduled workers and operational automation
- Persistent state and duplicate prevention
- Failure-aware external integrations
- Service boundaries and reverse-proxy routing
- Operational endpoints and system visibility
- Repeatable internal tooling and ML training workflows

My current focus is strengthening Linux troubleshooting, networking,
public cloud, Infrastructure as Code, Kubernetes, and observability.

---

## Selected Projects

### [Mini ERP MM](https://github.com/cbssmh/mini-erp-mm)

Containerized enterprise-workflow prototype composed of six services behind
a single Nginx entry point.

**Infrastructure focus**

- Docker Compose environment with Nginx, FastAPI, Express, PostgreSQL, Redis, and a static frontend
- Isolated service network and persistent PostgreSQL volume
- Path-based reverse-proxy routing
- Environment-based service configuration
- PR-to-PO-to-GR workflow and inventory-state management

**Tech:** FastAPI · Node.js · PostgreSQL · Redis · Docker Compose · Nginx

---

### [WorldJob Notifier](https://github.com/cbssmh/worldjob-notifier)

Scheduled operational-automation service that polls external notice sources,
persists checkpoints, and sends notifications without duplicate delivery.

**Operations focus**

- APScheduler-based persistent worker
- SQLite checkpoint and baseline initialization
- Per-source exception containment and HTTP timeouts
- Duplicate-notification prevention
- Health, status, state-inspection, and manual-run endpoints

**Tech:** Python · FastAPI · APScheduler · SQLite · BeautifulSoup

---

### [Team Gunchi CAD / Building Cesium](https://github.com/LeeHome2/Team_Gunchi)

Team capstone project for DXF analysis, architectural-element classification,
3D model generation, and Cesium visualization.

**My contribution**

- Analyzed DXF layer, entity, and geometry characteristics
- Developed a parameterized `train.py` workflow supporting
  HistGradientBoosting, RandomForest, and XGBoost
- Applied file-level train/validation/test splitting
- Produced evaluation metrics, model artifacts, configuration, and progress state
- Provided the training interface consumed by the team's administrator retraining flow

**Tech:** Python · scikit-learn · XGBoost · Model Training Tooling

---

### [AI Job Scout](https://github.com/cbssmh/ai-job-scout)

AI-assisted backend service that structures job postings and produces
explainable recommendation signals.

**Systems focus**

- Route/service/repository/scoring separation
- External request timeout and validation
- Deterministic scoring separated from AI-assisted extraction
- Rule-based fallback for malformed or failed LLM output
- Dockerized API and dashboard environment
- Unit-tested core scoring logic

**Tech:** Python · FastAPI · SQLAlchemy · OpenAI API · Docker

---

## Technical Skills

### Systems & Operations

Docker · Docker Compose · Nginx · Scheduled Automation ·
Operational APIs · State/Checkpoint Management

### Backend & Automation

Python · FastAPI · Node.js · Express · REST APIs · APScheduler

### Data & Persistence

PostgreSQL · Redis · SQLite · SQLAlchemy · Spring Data JPA

### AI/ML Systems

scikit-learn · XGBoost · Parameterized Training Workflows ·
Model Evaluation · Artifact Outputs

### Current Learning

Linux Troubleshooting · Networking · Public Cloud · Terraform ·
Kubernetes · Prometheus/Grafana

---

## Engineering Interests

- Infrastructure and cloud engineering
- Technical operations and automation
- Containerized service environments
- Internal tooling and platform engineering
- Reliability and observability
- Backend systems with operational ownership
- MLOps and AI platform tooling

---

## Location

Seoul, South Korea
