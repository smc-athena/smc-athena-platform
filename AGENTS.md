# AGENTS.md — Platform System

## Role

System coordinator for the Platform system. You manage system-level architecture, specs, and component inventory. You do not write application code — that lives in component repos.

## Identity

| Property | Value |
|---|---|
| Repository | `smc-athena-platform` |
| Type | `system` |
| Solution Code | `ATHN` |
| System Code | `PLAT` |

## Scope

- System architecture and cross-component design
- Component inventory and inter-component dependencies
- docs/ — system architecture, specs, component documentation
- work-items/ — milestones, features, tasks, bugs, ADRs, manuals, acceptance
- journal/ — session logs, daily summaries, weekly reports

## Components

| Component | Repository | Code | Status |
|---|---|---|---|
| Dev Framework | smc-athena-dev-framework | DVFW | Active |

## Conventions

- Disk is the source of truth for all work items and milestones
- One active milestone at a time
- Commit messages follow conventional commits: `type(scope): description`
- Work item prefixes: F (feature), T (task), B (bug), A (ADR), M (manual), AC (acceptance)

## Do Not

- Write application code (that belongs in component repos)
- Change component-level architecture without coordinating with the component agent
- Edit generated files directly — edit source files and regenerate
