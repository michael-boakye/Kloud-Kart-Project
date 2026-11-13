# ADR-001: Separate Management Reporting from the Live Website Database

- **Status:** Accepted
- **Date:** 2026-11-12
- **Decision owner:** Nana Adjei, Head of Operations

## Context

Kloud Kart runs its website, customer accounts, orders and inventory on one MySQL database server. Large Monday reporting exports have slowed the live website on two occasions in the previous month. A second server or read replica has already been approved.

## Decision

Kloud Kart will establish a separate reporting copy of its existing database and move suitable management reporting activities away from the live website database. The arrangement must be tested before reporting workloads are transferred.

## Alternatives considered

### Alternative A: Continue reporting from the live database

- **How it would work:** Operations and Finance would continue running large reports directly against the database supporting the live website.
- **Why it is attractive:** It requires no separate reporting environment and keeps reporting close to the original data.
- **Why rejected:** Reporting already coincides with website slowdowns. Continuing this arrangement leaves an identified operational risk unresolved.

## Consequences

- **What this buys:** Less competition between reporting activities and the live website for system resources, subject to successful testing.
- **What this costs:** Setup, monitoring, maintenance and the cost of operating the separate server.
- **What it costs the client if I am wrong:** The company could spend money on a separate environment without achieving the expected improvement. Replication could also introduce delays or additional workload.
- **What would make me revisit this:** If testing shows that the separate environment does not adequately protect website performance, or if reporting needs change substantially.

## What this survives

Higher order volumes, larger reporting exports and expansion into Nigeria can increase reporting demands without requiring management reports to run directly against the live website database. If the separate environment becomes inadequate, Kloud Kart can review its capacity without abandoning the principle of protecting live operations.
