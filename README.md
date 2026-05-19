# Talk-to-an-Expert — Dev Preview

Static preview of the unified signup page for teammate review.

- `?dev=1` — adds a Tier-override dropdown (test HIGH/MID/NON-ICP states without LLM)
- `?dev=2` — same + bypasses the personal-email block (allows `test@*` for E2E testing)
- Default (no flag) — production routing via LLM router

NOTE: this is a static deploy for UI/flow review only. LLM router calls will fail CORS from this origin — that's expected. To exercise real classification, use the live site.
