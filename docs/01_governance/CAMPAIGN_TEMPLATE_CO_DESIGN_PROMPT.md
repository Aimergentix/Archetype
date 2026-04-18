# Campaign Template Co-Design Protocol (Wesnoth 1.19)

This repository uses a phased co-design process for AI-assisted campaign template work.

## Working contract

- Proceed phase by phase, stage by stage.
- Do not skip ahead.
- End each stage with a concise summary and explicit confirmation request.
- If uncertain about API/tag/mechanic details, stop and mark `# [NEEDS REVIEW]`.
- Apply normative source ordering from `docs/01_governance/GenAI_META.md`.

## Phase map

1. **Phase 0 — Context bootstrap**
   - Stage 0.1 Mode declaration (`FRAMEWORK_BOOTSTRAP`) and file-scope confirmation.
   - Stage 0.2 Wesnoth 1.19 API baseline audit (VERIFIED_DOC vs NEEDS_REVIEW).
   - Stage 0.3 Consolidated hard-constraint inventory.
2. **Phase 1 — Dramatic spine design**
3. **Phase 2 — State schema design**
4. **Phase 3 — Novel mechanics design**
5. **Phase 4 — WML/Lua scaffold generation**
6. **Phase 5 — Balance and playtest specification**
7. **Phase 6 — Documentation package**

## Session startup instruction

Begin with **Phase 0, Stage 0.1** only:

- Declare active task mode: `FRAMEWORK_BOOTSTRAP`.
- Confirm framework files in scope.
- List referenced but absent files and flag each as `# [NEEDS REVIEW]`.
- Wait for project-owner confirmation before Stage 0.2.
