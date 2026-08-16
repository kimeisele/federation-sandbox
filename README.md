# federation-sandbox

FAW sandbox target repository (Federation Bootstrap D1/D4).

**Purpose:** destination of the bounded mutation for the vertical slice. The
FAW runtime writes only `faw/attempt/<attempt_id>` branches — never `main`,
never PRs (D1).

**Governance:** `main` is branch-protected (no force-pushes, no deletions,
admins enforced). The first delegation will carry `max_wall_seconds` and
`max_output_bytes` only (D5).

**Contents:** intentionally boring, bounded tasks (per §10 of the program
brief). This repo demonstrates the system boundary, not intelligence.
