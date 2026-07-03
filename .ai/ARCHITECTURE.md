# Architecture

This document defines the project architecture at the governance level.

Rachel Capital uses five layers so that investment knowledge, portfolio operations, engineering work, delivery workflow, and governance rules do not collapse into one undifferentiated system.

## Layer Model

| Layer | Scope | Core Artifacts | Owner |
| --- | --- | --- | --- |
| Knowledge Layer | Stable investment knowledge and analysis | Investment Principles; Trading Rules; Thesis; Research | ChatGPT |
| Portfolio Layer | Current portfolio state and decision records | Dashboard; Account; Decision Log; Watchlist | ChatGPT / Codex |
| Engineering Layer | Future system implementation | Python; Scripts; Automation | Codex |
| Workflow Layer | Change management and delivery | GitHub; Pull Requests; Sprint; Release | Codex |
| Governance Layer | Long-term operating rules | Rules; Architecture; Workflow | Both |

## Why The Layers Exist

### Knowledge Layer

This layer holds durable thinking.

It exists so that investment reasoning can be maintained independently from portfolio snapshots or engineering changes.

### Portfolio Layer

This layer holds the current operating state.

It exists so that active decisions, capital positioning, and portfolio review can be seen quickly without mixing them with long-form research.

### Engineering Layer

This layer holds implementation work.

It exists so future tools, scripts, dashboards, and automation can be built without distorting the knowledge system.

### Workflow Layer

This layer holds delivery discipline.

It exists so every change moves through a consistent GitHub-based lifecycle instead of relying on ad hoc edits.

### Governance Layer

This layer holds the rules of the project itself.

It exists so roles, standards, reviews, and architectural constraints remain stable over time.

## Architecture Rules

- Each layer should have a clear purpose.
- Documents should not duplicate responsibilities across layers.
- Every document must either guide a decision or preserve investment memory. Otherwise, it should not exist.
- Changes to one layer should not force unnecessary change in another layer.
- Governance and workflow should remain understandable without reading chat history.
- Engineering should support the knowledge system, not dominate it.

## Ownership Rules

- ChatGPT owns the quality of the knowledge layer.
- Codex owns the quality of the engineering and workflow layers.
- The portfolio layer is shared because it depends on both decision support and system structure.
- The governance layer is shared because both operating judgment and system discipline are required to maintain it.
