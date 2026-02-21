# AIDEX (AI Development Excellence & Traceability Standard)
The open framework for certifying human accountability, source integrity, and structural transparency in AI-assisted software engineering.

## The Manifesto

As AI becomes an integral part of the software development lifecycle, the line between human intent and machine execution blurs. The AIDEX is an open-source standard designed to restore accountability. We believe that every line of AI-generated code must be traceable, and every autonomous agent must have a human heartbeat behind it.

## Core Principles

1. **The Public Human-in-Loop (PHiL)**: Every organizational AI deployment must have a designated, public-facing human responsible for its configuration and ethical behavior.

2. **Mandatory Source Tagging**: All AI-generated code must include metadata headers in the source files, including generation proofs and a log of subsequent human modifications.

3. **Architectural Transparency**: AI roles and their interconnections within an organization must be explicitly mapped to prevent "shadow automation" and unaccountable feedback loops.


## Levels

### Tier 1: Silver (Self-Certified)

Targeted at individual developers and open-source contributors.

- **Self-Declaration**: The maintainer includes the AIDEX_MANIFESTO.md and a basic CERTIFICATION.json.

- **Manual Tagging**: All AI-generated blocks are marked with @ai-generated comments.

- **Human Oversight**: A public profile (GitHub/LinkedIn) is linked as the primary supervisor.

- **Trust-Based**: Compliance is based on the developer's integrity and community reporting.

### Tier 2: Gold (Audited & Verified)

Targeted at enterprises, financial systems, and critical infrastructure.

- **Automated Verification**: Use of the AIDEX-Linter to verify commit timestamps and code entropy, ensuring no "shadow AI" blocks exist.

- **Prompt Provenance**: Every AI-generated module must include a PROMPT_HASH or a link to the generation log (e.g., API request ID).

- **Interconnection Mapping**: A mandatory ARCHITECTURE_ROLES.json defining the flow between AI agents and human approval gates.

- **Audit Trail**: Full traceability of modifications from the initial AI output to the current production version.

- **External Validation**: Periodic review of the AI-Human interaction logs by the AIDEX community or an authorized auditor.
