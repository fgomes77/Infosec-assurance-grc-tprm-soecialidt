# Infosec-assurance-grc-tprm-soecialidt

Information security assurance, GRC and third-party risk management working
repository.

## Contents

| Path | What it is |
|---|---|
| `claude-account-export/` | Backup of the Claude account's skill and capability surface — 35 account-synced skills (18 custom GRC/TPRM), 41 Anthropic platform skills (8 public, 33 examples), the authored advisor knowledge pack, `PERSONA.md`, `CAPABILITIES.md`, `environment/` |
| `convertion/` | Azure AI Foundry conversion kit — turns the export above into deployable Foundry agents (Bicep infra, MCP server, OpenAPI integrations, workflows, governance) |
| `project-dossier/` | Project dossier for the InfoSec Assurance Agent Platform — `.docx`, infographics and their generators |

`convertion/` reads `claude-account-export/` as a sibling directory
(`convert_skills.py`, `verify_conversion.py`), so the two are kept together
here.

## Relationship to `infosec-assurance-azure-foundry`

This repository and
[`fgomes77/infosec-assurance-azure-foundry`](https://github.com/fgomes77/infosec-assurance-azure-foundry)
were maintained as mirrors up to 2026-09-12 and still share the content above.

**They are no longer synchronised.** From 2026-09-12 each repository evolves
independently: changes made here do not propagate there, and changes made there
do not propagate here. Any future alignment is a deliberate, manual act.
