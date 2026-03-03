# smc-athena-platform

Platform system — cross-cutting tooling and framework components for the Athena ecosystem.

## Overview

The Platform system (`ATHN/PLAT`) provides shared infrastructure, tooling, and framework components that support all other systems in the Athena solution. It does not deliver business-domain functionality — it delivers the foundation that business-domain systems build on.

## Components

| Component | Repository | Code | Description |
|---|---|---|---|
| Dev Framework | [smc-athena-dev-framework](https://github.com/smc-athena/smc-athena-dev-framework) | `DVFW` | Development framework — guides, skills, conventions, and schemas |

## What This Repo Contains

This is a **system repository** — it holds system-level coordination artifacts, not application code:

- **docs/** — system architecture, cross-component design, specs
- **work-items/** — milestones, features, tasks, bugs, ADRs, manuals, acceptance criteria
- **journal/** — session logs, daily summaries, weekly reports

## Hierarchy

```
smc-athena (Solution: ATHN)
└── smc-athena-platform (System: PLAT)
    └── smc-athena-dev-framework (Component: DVFW)
```
