<h1 align="center">🧪 Docker Pipeline Test</h1>

<p align="center">
  <em>Docker Compose environment for testing CI/CD pipelines and automation workflows</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
</p>

<p align="center">
  <a href="README.de.md">🇩🇪 Deutsche Version</a>
</p>

---

## 📖 About

A Docker Compose configuration for setting up a local pipeline testing environment. Ideal for validating CI/CD workflows and automation scenarios before deploying to production.

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container runtime |
| ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) Docker Compose | 1.29+ | Orchestration |

## ✨ Features

- **Isolated environment** — Test pipelines safely in containers
- **Reproducible** — Same configuration every run
- **Easy cleanup** — Tear down test environment quickly

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-pipeline-test.git
cd docker-pipeline-test
docker compose up -d
```

## 📋 Usage

```bash
# Start test environment
docker compose up -d

# View logs
docker compose logs -f

# Clean up
docker compose down
```

## 📄 License

Released under the MIT License.
