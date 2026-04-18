# MP Sync and Carryover Reference

This reference defines baseline constraints for Archetype template work.

## MP OOS safety baseline

- Treat gameplay-affecting writes as synchronized-only operations.
- Avoid side effects in unsynchronized UI-only contexts.
- Keep randomization deterministic and synchronized across clients.
- Ensure scenario-end state writes happen in deterministic victory/defeat paths.

## Carryover baseline

- Gold carryover policy must be explicitly defined per scenario boundary.
- Unit carryover eligibility must be explicit (persistent vs scenario-local).
- Persistent variables must be namespaced and documented.
- Branch-dependent variables must converge into Epilogue-readable state.
