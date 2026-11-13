# ADR-003: Build a Modest Reporting Capability Before Investing in a Large Data Platform

- **Status:** Accepted
- **Date:** 2026-11-12
- **Decision owner:** Nana Adjei, Head of Operations

## Context

Kloud Kart processes approximately 4,000 orders daily and has a database of about 40 GB. It has one PHP/MySQL developer, no established data team and funding for only two data hires. The developer has suggested a larger cloud-based data platform, while Finance is concerned about the cost.

## Decision

Kloud Kart will begin with its existing MySQL environment, a separate reporting copy and controlled management reports. It will not invest in a large data warehouse or lakehouse during the initial implementation.

## Alternatives considered

### Alternative A: Introduce a large cloud-based data platform immediately

- **How it would work:** Move business information into a separate, larger data platform and build reporting around that environment.
- **Why it is attractive:** It could support more data sources, advanced analysis and future expansion.
- **Why rejected:** The company has not yet established consistent reporting or the specialist team needed to manage a more complex platform. Introducing it now would add cost and management demands before the immediate problems have been resolved.

## Consequences

- **What this buys:** A more manageable starting point, lower initial complexity and a system that builds on the company's existing database skills.
- **What this costs:** The company may need to make further investments if its reporting requirements outgrow the initial arrangement.
- **What it costs the client if I am wrong:** The initial system could become inadequate sooner than expected, requiring additional work and migration.
- **What would make me revisit this:** Significant growth in data volume, more complex reporting across countries or systems, or clear evidence that the existing approach can no longer meet business requirements.

## What this survives

The approach allows Kloud Kart to grow its reporting capability in stages. If investor expectations increase or the Nigeria operation expands, the company can review the platform based on actual business needs and evidence rather than committing to a larger system prematurely.
