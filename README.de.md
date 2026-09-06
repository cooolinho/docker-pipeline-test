<h1 align="center">🧪 Docker Pipeline Test</h1>

<p align="center">
  <em>Docker Compose-Umgebung zum Testen von CI/CD-Pipelines und Automatisierungs-Workflows</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
</p>

<p align="center">
  <a href="README.md">🇬🇧 English version</a>
</p>

---

## 📖 Über das Projekt

Eine Docker Compose-Konfiguration zum Einrichten einer lokalen Pipeline-Test-Umgebung. Ideal zum Validieren von CI/CD-Workflows und Automatisierungs-Szenarien vor der Bereitstellung in der Produktion.

## 🛠️ Tech-Stack

| Technologie | Version | Zweck |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container-Laufzeit |
| ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) Docker Compose | 1.29+ | Orchestrierung |

## ✨ Funktionen

- **Isolierte Umgebung** — Teste Pipelines sicher in Containern
- **Reproduzierbar** — Gleiche Konfiguration bei jedem Lauf
- **Einfache Bereinigung** — Test-Umgebung schnell abreißen

## 🚀 Erste Schritte

### Voraussetzungen

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-pipeline-test.git
cd docker-pipeline-test
docker compose up -d
```

## 📋 Verwendung

```bash
# Test-Umgebung starten
docker compose up -d

# Logs anzeigen
docker compose logs -f

# Aufräumen
docker compose down
```

## 📄 Lizenz

Freigegeben unter der MIT-Lizenz.
