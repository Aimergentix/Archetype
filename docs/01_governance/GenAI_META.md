# GenAI Meta Governance

## ROLE AND OBJECTIVE

Archetype is a reusable UMC campaign template for Battle for Wesnoth 1.19.
AI-assisted work in this repository must preserve portability across single-player,
co-op multiplayer, and competitive multiplayer modes.

### Normative source priority

When sources conflict, resolve in this strict order:

1. Battle for Wesnoth 1.19 engine behavior (as observed in-game) and official 1.19 documentation.
2. Repository source files and technical contracts in this project.
3. Repository governance files in `docs/01_governance/`.
4. Repository reference guidance in `docs/02_reference/`.
5. External examples and prior general Wesnoth knowledge.

If a required source is missing, mark the exact point as `# [NEEDS REVIEW]`.
