# Joshua Angulo González

**Software Engineer — Backend, Full-Stack y Datos** · Culiacán, Sinaloa, México

Convierto necesidades operativas en productos digitales de punta a punta: APIs REST, plataformas multi-tenant, sistemas distribuidos en tiempo real y pipelines de datos a gran escala. Integro seguridad, validación y observabilidad desde el diseño, no como un añadido al final.

## Stack

- **Lenguajes** · TypeScript · JavaScript · Python · SQL · Rust
- **Backend** · Node.js · Express · APIs REST · OAuth 2.0 y JWT · SSE y WebSockets · colas de trabajo · sistemas distribuidos
- **Datos** · PostgreSQL · Supabase · MongoDB · Redis · DuckDB · Polars · Parquet
- **Frontend** · React · Next.js · Vite · Tailwind CSS
- **Infraestructura** · Docker · Linux · AWS · GitHub Actions · CI/CD
- **Calidad y observabilidad** · Vitest · Playwright · OpenTelemetry · Sentry · Prometheus
- **IA y ML** · agentes LLM · tool calling · RAG y embeddings · XGBoost · CatBoost · scikit-learn

## En qué trabajo

Los dos proyectos que sostienen mi experiencia están en repositorios privados: uno es producto propio en desarrollo y el otro contiene estrategia propia. La arquitectura y las decisiones de ambos sí están escritas y son públicas:

**→ [case-studies](https://github.com/joshua-angulo/case-studies)** — notas de ingeniería sanitizadas: qué se construyó, qué decisiones lo sostienen y qué haría distinto.

**→ [multi-tenant-rls](https://github.com/joshua-angulo/multi-tenant-rls)** — código ejecutable: aislamiento entre clientes con Row Level Security en PostgreSQL, con 16 pruebas en su mayoría negativas y verificación por mutación.

### LuckAgents — plataforma SaaS multi-tenant de agentes de IA · 2025 – presente

Monorepo de 10 workspaces: API en Express, dashboard React/Vite, portal Next.js y un runtime de agentes en contenedores, sobre PostgreSQL/Supabase, MongoDB y Redis.

- Aislamiento de datos por cliente con SSO/OAuth 2.0, RBAC y 31 políticas RLS.
- 1,066 pruebas automatizadas: 619 de API, 371 unitarias y de UI, 76 E2E.
- CI/CD en GitHub Actions con CodeQL y revisión de dependencias; una auditoría de modernización llevó de 155 a 0 las vulnerabilidades conocidas en dependencias de producción.
- Integraciones con Stripe, WhatsApp Business API, Google Calendar y AWS S3 mediante webhooks idempotentes, instrumentadas con OpenTelemetry, Sentry y Prometheus.

### Plataforma cuantitativa para mercados electrónicos · 2026 – presente

Runtime asíncrono en Rust (Tokio) que consume WebSockets en tiempo real, reconstruye libros de órdenes y usa aritmética decimal en los cálculos monetarios.

- Pipeline de investigación en Python con Parquet, Polars y DuckDB sobre decenas de millones de registros de series temporales; modelos tabulares con XGBoost, CatBoost y LightGBM.
- Disciplina de auditoría: validación walk-forward, control de fuga temporal, manifiestos SHA-256, pruebas negativas de integridad y paridad de resultados entre Python y Rust.

## Formación

- **Ingeniería Industrial, titulado** — Universidad Tecmilenio, Campus Culiacán · 2021 – 2025
- **Materias de posgrado en Ciencias de la Computación** — Universidad Autónoma de Sinaloa
- Español nativo · **inglés C1**

## Contacto

Abierto a posiciones de backend o full-stack, en México o remoto.

- [linkedin.com/in/joshuaangulogonzalez](https://www.linkedin.com/in/joshuaangulogonzalez/)
- [joshuaangulo10@gmail.com](mailto:joshuaangulo10@gmail.com)

---

**In English.** I'm a software engineer working across backend, full-stack and data. I build products end to end — REST APIs, multi-tenant platforms, real-time distributed systems and high-volume data pipelines in TypeScript/Node.js, Python and Rust — with security, automated testing and observability designed in from the start. Most of my work lives in private repositories; I'm glad to walk through the architecture and the code in an interview.
