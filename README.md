# Hey, I'm Andrew

CS graduate from UMass Amherst. Sole internal software developer at New England Money Handling Systems, where I build production tooling for the technicians who service cash recyclers, ATMs, and bill counters across southern New England. Outside work, I'm into PC building and hardware tinkering.

## About Me

- **Interests:** Applied AI, Hardware, Web Dev, Automation
- **Pronouns:** He/Him

## Tech Stack

**Languages**

[![My Skills](https://skillicons.dev/icons?i=python,ts,js,java&perline=8)](https://skillicons.dev)

**Frameworks & Tools**

[![My Skills](https://skillicons.dev/icons?i=fastapi,react,vite,nodejs,docker,azure,redis,sqlite,git&perline=8)](https://skillicons.dev)

**Domain:** Cash recycler / ATM diagnostics · hardware integration · field-tech workflow design

## Currently Building

### Judge — multi-model diagnostic platform for Glory cash recyclers

FastAPI backend + React / TypeScript frontend, deployed on Azure.

- Turns 1,150+ pages of vendor error documentation into a searchable, schematic-aware interface — **tap an error code, see the part on the machine**. Live for **RBG-100** (392 codes) and **GLR-100** (754 codes) from a single configuration.
- **"Ask Judge"** — a remote MCP connector that exposes Judge's grounded diagnostics inside Claude: symptom diagnosis, multi-code error-sequence correlation, code lookup, and step-by-step repair workflows.
- 60+ guided repair workflows with 460+ field-captured photos; interactive hardware diagrams with component highlighting and auto-zoom.
- Hardened for multi-tenant SaaS: Azure AD single sign-on, a tamper-evident hash-chained audit log, per-customer access rules, rate limiting, and an encryption-at-rest boot check.
- 1,300+ backend tests plus component and Playwright e2e suites gate every Azure deploy (ACR + App Service, Docker).

### Custos — fleet telemetry for Cassida Pro Zeus discriminators

Started as two-way USB serial I/O for Cassida Pro Zeus currency discriminators — device enumeration and scriptable commands where the vendor ships Windows-only software. It's grown into a fleet-telemetry layer: passive monitoring of count statistics, reject rates, and device health across deployments.

## Connect

- [LinkedIn](https://www.linkedin.com/in/aspiezio)
- [Portfolio](https://ajspiezio.github.io/)
