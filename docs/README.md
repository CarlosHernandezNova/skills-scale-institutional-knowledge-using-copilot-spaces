# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management knowledge base. This documentation provides guidance for managing projects, delivering features, and scaling institutional knowledge across teams.

## OctoAcme Project Management Processes Overview

OctoAcme utiliza un enfoque de gestión de proyectos basado en un ciclo claro y repetible: **iniciación, planificación, ejecución, liberación y cierre/retrospectiva**. En la fase de iniciación, el equipo valida la necesidad de negocio, define objetivos, identifica interesados y documenta un "one-pager" con problema, métricas de éxito, cronograma y riesgos iniciales. Luego, en la planificación, convierten la iniciativa en un backlog priorizado, estiman esfuerzo, definen criterios de aceptación y establecen un plan de entregas con dependencias, hitos y definición de hecho. Durante la ejecución, el trabajo se gestiona con tableros de proyecto, reuniones de seguimiento y entregas iterativas pequeñas, con la intención de mantener flujo constante y facilitar ajustes tempranos. El cierre incluye retrospectivas para documentar aprendizajes y convertirlos en mejoras continuas.

El modelo de roles de OctoAcme está bien definido para sostener ese flujo. Los **Project Managers** coordinan cronogramas, riesgos, comunicaciones y documentación, mientras que los **Product Managers** definen la visión, priorizan el backlog y miden impacto. Los **desarrolladores** implementan soluciones, escriben pruebas y mantienen la calidad técnica, mientras que **QA/Testing** valida que se cumplan los criterios de aceptación. Esta separación de responsabilidades ayuda a mantener claridad de ownership y alinea objetivos del negocio con el equipo técnico.

La **comunicación** es un eje central del proceso. OctoAcme recomienda reuniones regulares como standups diarios, sincronizaciones semanales de entrega, revisiones de sprint o hitos, y actualizaciones periódicas a stakeholders. Se establece un escalamiento de bloqueadores y riesgos por niveles: equipo, PM, líderes de producto, y sponsor. Además, se promueve un "single source of truth" para el estado del proyecto, asegurando que todos reciban la misma información.

En cuanto a **calidad y aseguramiento**, OctoAcme exige disciplina en cada entrega. Se trabaja con PRs pequeños, inclusión de enlace a incidencia, pruebas automáticas, linting y análisis de seguridad en CI. También se recomienda pruebas unitarias, integración y smoke tests para flujos críticos. La definición de hecho y los checklist de release ayudan a asegurar que cada cambio cumple con criterios de calidad antes de salir a producción.

---

## Quick Navigation

### Core Principles
OctoAcme operates on five core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle

1. [**Initiation**](./octoacme-project-initiation.md) — Validate business need, identify stakeholders, create a lightweight plan
2. [**Planning**](./octoacme-project-planning.md) — Break work into shippable increments, define timeline and dependencies
3. [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Day-to-day delivery, progress tracking, and quality assurance
4. [**Release & Deployment**](./octoacme-release-and-deployment.md) — Standardize releases, manage rollbacks, and reduce production risk
5. [**Retrospective & Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and drive continuous improvement

### Complete Documentation

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction and communication cadence
- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of Developer, Product Manager, Project Manager, and Stakeholder roles
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk registers, escalation paths, and stakeholder updates

### How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) flow
- **Managing execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management](./octoacme-risks-and-communication.md)
- **Preparing to release?** See [Release & Deployment](./octoacme-release-and-deployment.md)
- **Reflecting on a milestone?** Use [Retrospective & Improvement](./octoacme-retrospective-and-continuous-improvement.md)

---

## Key Artifacts Used in OctoAcme

- **Project Charter / One-pager** — Business case, success metrics, stakeholders
- **Roadmap and Release Plan** — Timeline of features and milestones
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria
- **Risk Register** — Identified risks, impact, mitigation plans
- **Retrospective notes** — Learnings and action items for continuous improvement

---

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly PM + PdM sync** — Alignment and decision-making
- **Twice-weekly delivery team standups** — Or as agreed
- **Monthly stakeholder updates** — Status and announcements
- **Ad-hoc escalations** — As needed for risks and blockers asdfadfadsfadf 
