# v1.4 — Nami KO protection

- When an eligible Straw Hat Crew character would be KO’d in **combat**, an active Green Nami OP17-023 can be rested instead after user confirmation.
- Declining the prompt allows the KO to proceed. A rested Nami cannot replace another KO until refreshed.
- Supports saving/restoring Nami rested status through existing match save format.
- Keeps Brook, Shanks, GitHub Pages and offline HTML versions.

## Scope and limitations
- Only combat KO currently calls the replacement handler; future card-effect KOs need to call it too.
- Crew eligibility is a **training mapping** based on identified Straw Hat names, not a complete verified card-type database. Characters outside the mapping are not automatically protected.
- The current opponent demo only attacks the Leader, so testing protection requires a sandbox combat scenario that targets one of your Characters; a new demo opponent Character attack button provides a test path.
- Card effects and DON!! timing remain incomplete; this is not a tournament-accurate simulator.
