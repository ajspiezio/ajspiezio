# Hey, I'm Andrew

CS graduate from UMass Amherst. Sole internal software developer at New England Money Handling Systems, where I build production tooling for the technicians who service cash recyclers, ATMs, and bill counters across southern New England. Outside work, I'm into PC building and hardware tinkering.

## About Me

- **Interests:** Applied AI, Hardware, Web Dev, Automation
- **Pronouns:** He/Him

## Tech Stack

**Languages**

[![My Skills](https://skillicons.dev/icons?i=python,ts,js,java&perline=8)](https://skillicons.dev)

**Frameworks & Tools**

[![My Skills](https://skillicons.dev/icons?i=fastapi,react,vite,nodejs,docker,azure,redis,sqlite,githubactions,git&perline=10)](https://skillicons.dev)

**Domain:** Cash recycler / ATM diagnostics · hardware integration · field-tech workflow design · MCP connectors

## Currently Building

### Judge: diagnostics and field operations for Glory cash recyclers

FastAPI backend, React / TypeScript frontend, deployed on Azure. Currently at v11.1 after 1,000+ commits.

- **Ask Judge**, a remote MCP connector that puts Judge inside Claude: 10 read-only tools for symptom diagnosis, error-sequence correlation, code and component lookup, reference search, and repair workflows. It also covers the **RBU-11** (386 codes), which is available only through the connector. Judge runs no LLM of its own & only returns manual-grounded answers.
- **Log diagnosis.** Upload a machine's native log dump and Judge resolves every code against the manual, pins the parts on the schematic, and ranks an inspection order. Manual facts and inferred correlations are kept apart, so an inspection order never gets passed off as a root cause.
- 62 guided repair workflows with 466 field photos, plus jam-zone maps and RAS troubleshooting codes.
- **Field operations.** Judge has grown past diagnostics into the app techs use on the job: paperless installs (a QR sticker per machine, checklists on a phone, a signed PDF that replaces three paper forms), expense reports routed to the right manager, vehicle inspections, and an ATM site-survey wizard.
- Multi-tenant security: Entra ID single sign-on, four roles, a tamper-evident hash-chained audit log, per-customer access rules, rate limiting, and an encryption-at-rest boot check.
- 2,400+ backend tests, 1,500+ frontend tests, and 45 Playwright e2e specs gate every Azure deploy (ACR + App Service, Docker).

### Custos: fleet telemetry for Cassida Pro Zeus discriminators

Started as two-way USB serial I/O for Cassida Pro Zeus currency discriminators, where the vendor only ships Windows software. It's now a passive fleet-telemetry layer that reports count statistics, reject rates, and device health from bank sites. It needs no admin rights or installer and opens no inbound network surface.

### Smaller tools

- **Judge-Leverage-Tool**: finds new Glory installs in our Leverage service system and emails the install lead a pre-filled Judge link for each one.
- **Tomb Stack**: a Raycast extension that collects several clipboard items to hand to Claude at once and archives them into my Obsidian vault.

## Connect

- [LinkedIn](https://www.linkedin.com/in/andrew-spiezio/)
- [Portfolio](https://ajspiezio.github.io/)
