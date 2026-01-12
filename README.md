# SaaS Metrics Standards
An Open Source Implementation

## The Objective
In high-growth SaaS, a frequent and discernible disconnect exists between the business processes that run the company and the valuation metrics that ultimately judge it. Since a favorable valuation is the commercial destination of any SaaS enterprise, clear and universally understood metrics are not just reporting tools—they are the requirements for success.

Standardized metrics allow SaaS operators to work backward from valuation outcomes to intentionally improve input systems, behaviors, decisions, and investments. This repository is dedicated to advancing the work of the [SaaS Metrics Standards Board](https://www.saasmetricsboard.com/) by moving these standards into an accessible, collaborative, technically-capable, and version-controlled environment.

By open-sourcing these definitions and their technical instrumentation, we move the industry away from "black-box" reporting and toward an audit-ready Single Source of Truth.

## The GTM Data Operating Framework
To operate with the "end in mind," we utilize the following framework to align ground-level inputs with executive-level outcomes:

$$Business\ Valuation\ Metrics \leftarrow Operating\ KPIs \leftarrow Information \leftarrow Analysis \leftarrow Data \leftarrow Systems \leftarrow Processes$$

When metrics are standardized and meaningful, they become the "North Star" for all operating activities, ensuring that every system and process is engineered for maximum efficiency and value creation.

## Origin of the Standards
The definitions and equations housed in this repository are derived from the [foundational work](https://www.saasmetricsboard.com/standards) established by the SaaS Metrics Standards Board. The goal of this project is to provide a collaborative space where the global GTM community can contribute to, refine, and build code-based implementations (SQL/dbt) for a common schema.

## Important Notes & Disclaimers
**Authorization.** This repository is an independent project and is being created without formal authorization from the SaaS Metrics Standards Board. It is intended as a community-driven extension of their published work.

**Licensing.** This project is currently released under the MIT License. This is a permissive license to encourage widespread adoption and contribution, though it is subject to change as the project evolves and formalizes.

## Strategic Roadmap
Phase 1: Move all core definitions (ARR, NRR, CAC, LTV, etc.) and mathematical equations into standardized Markdown files.
Phase 2: Invite community peer review and alignment on edge-case logic (e.g., partial-month churn, expansion timing).
Phase 3 (Future): Develop exemplar SQL/dbt models to demonstrate how these metrics are calculated from raw transactional data.
