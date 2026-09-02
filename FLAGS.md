# FLAGS

Improvement register for this repository. Documentation handover only - do not treat Open rows as bugs fixed in the docs PR.

Status: **Open** (actionable later) or **Accepted** (known limitation).


| ID | Severity | Finding | Evidence | Suggested next step | Status |
| --- | --- | --- | --- | --- | --- |
| F1 | Low | Root README was still create-next-app boilerplate at handover. | README | Keep README describing Guess the Tech. | Accepted |
| F2 | Medium | Production needs Supabase; SQLite fallback is not durable on Vercel. | DEPLOYMENT.md | Enforce Supabase env on production deploys before the next event. | Open |
| F3 | Low | ``plan.md`` is a product/design sketch, not operating STATE. | plan.md | Use docs/state.md for milestone; leave plan.md as historical task notes. | Accepted |