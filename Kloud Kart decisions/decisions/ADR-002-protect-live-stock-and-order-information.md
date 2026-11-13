# ADR-002: Keep Stock and Order Decisions on the Live System

- **Status:** Accepted
- **Date:** 2026-11-12
- **Decision owner:** Nana Adjei, Head of Operations

## Context

Kloud Kart must prevent stock information from becoming outdated because inaccurate stock counts can lead to overselling. A separate reporting copy may not always reflect the latest transactions immediately.

## Decision

The live operational system will remain the authoritative source for stock availability and order processing. The separate reporting environment will be used for management information that can safely refresh daily, not for live stock or order decisions.

## Alternatives considered

### Alternative A: Use the reporting copy for stock decisions

- **How it would work:** Staff and systems would use stock information from the reporting copy instead of checking the live operational system.
- **Why it is attractive:** It would allow stock information to be included in the same environment as management reports.
- **Why rejected:** Changes made in the live system may take time to appear in the reporting copy. Staff could therefore act on outdated stock figures and accept orders for items that are no longer available.

## Consequences

- **What this buys:** Protects stock accuracy by keeping operational decisions connected to the current source of stock information.
- **What this costs:** Stock information must continue to be managed through the existing operational system rather than relying on one reporting environment for every business need.
- **What it costs the client if I am wrong:** Keeping stock decisions on the existing system may limit future reporting or operational improvements if that system becomes inadequate.
- **What would make me revisit this:** Evidence that the operational system can no longer support stock and order activities reliably, or a properly tested alternative that can guarantee sufficiently current stock information.

## What this survives

Increased order volumes and expansion into Nigeria will not justify accepting outdated stock information for convenience. Any future change must demonstrate that it protects stock accuracy and prevents overselling before it replaces the current arrangement.
