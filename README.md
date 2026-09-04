# guardrail-auto-loan-underwriting

Auto-generated guardrail repository for **Auto Loan Underwriting** (Consumer Finance, structured).

- `policies/rules.rego` -- the Open Policy Agent policy. Start here.
- `policies/rules_test.rego` -- run with `opa test policies/`.
- `middleware/safety_hook.py` -- Python wrapper that shells out to `opa eval` to enforce the policy at inference time.
- `REGULATORY_PROVENANCE.md` -- which regulation(s) motivated this repo, and what they require.
- `metadata.json` -- machine-readable version of the same provenance, for the LegalGuard app to read back.

This repo was opened as a **pull request**, not committed straight to `main` --
review it like any other change before merging. See the parent project's
[docs/ARCHITECTURE.md](https://github.com/) note on what LegalGuard generates
automatically versus what still needs a human.
