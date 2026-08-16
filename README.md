# federation-sandbox

FAW sandbox target repository (Federation Bootstrap D1/D4).

**Purpose:** destination of the bounded mutation for the vertical slice. The
FAW runtime writes only `faw/attempt/<attempt_id>` branches — never `main`,
never PRs (D1).

**Governance:** `main` is branch-protected (no force-pushes, no deletions,
admins enforced).

**First bounded task (P6 §10):** "add a docstring to function `f` in `x.py`
and leave everything else unchanged." — see `x.py`. The task is intentionally
boring: it demonstrates the system boundary, not intelligence.
