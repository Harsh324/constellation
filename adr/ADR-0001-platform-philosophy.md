# ADR-0001

## Title

Separate Platform and Applications

## Status

Accepted

## Context

Applications should remain portable and independently deployable.

Infrastructure should not contain application-specific logic.

## Decision

Constellation owns infrastructure.

Applications own:

- Source code
- Dockerfiles
- Deployment
- Releases

## Consequences

- Cleaner repositories
- Easier migration
- Better scalability
- Independent deployments