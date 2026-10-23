# 🛡️ Saba Security Audit POC — SabaTech

> Landing demo del servicio de Auditoría de Seguridad para Sistemas de IA y Agentes Autónomos de SabaTech.

## 🎯 Qué es esto

POC (Proof of Concept) que presenta el servicio de Auditoría de Seguridad IA de SabaTech:

- **OWASP Agentic Applications Top 10** — prompt injection, tool abuse, identity spoofing, memory poisoning, supply chain de modelos, etc.
- **EU AI Act** — clasificación de riesgo, obligaciones de transparencia y gobernanza de datos.
- **NIST AI RMF** — evaluación estructurada del ciclo de vida de los sistemas de IA (Govern / Map / Measure / Manage).
- **Entregables claros** — informe ejecutivo + técnico, hallazgos por severidad, plan de remediación priorizado y re-test de verificación.
- **Motor técnico propio** — QA-FRAMEWORK (security testing OWASP, SAST, auditoría de dependencias) + capacidades OSINT, combinados con revisión experta.

## 🚀 Quick Start

### Opción 1: Docker (recomendado)

```bash
docker build -t saba-security-audit-poc .
docker run -p 8081:80 saba-security-audit-poc
# Abrir http://localhost:8081
```

### Opción 2: Servidor local

```bash
python3 -m http.server 8081
```

Abrir `http://localhost:8081` en el navegador.

## 📁 Estructura

```
saba-security-audit-poc/
├── index.html      # Landing page (single page, self-contained, dark mode)
├── Dockerfile      # nginx:alpine
└── README.md       # Este archivo
```

## ⚠️ Nota

**Todos los datos mostrados son simulados/demo.** No contienen información de infraestructura real: los mockups (gráfico de severidades, entregables) son CSS/SVG propios.

## 📄 Licencia

© 2026 SabaTech — Demo POC
