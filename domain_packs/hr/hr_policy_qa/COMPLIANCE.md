# DISABLED IN THIS PORTFOLIO FORK

`hr_policy_qa` is **not an HR or legal product**. The route returns HTTP 403 while `REGULATED_PACKS_ENABLED=false` (the default).

# Compliance Considerations — HR Policy Q&A

**This pack answers questions from supplied policy text. It does not provide legal or binding HR advice.**

## Regulatory context (non-exhaustive)

- **GDPR / Law 25**: Employee questions may involve personal situations; logging and retention need a lawful basis.
- **Automated processing**: If answers influence employment decisions, transparency and human review may be required.
- **Wrong answers**: RAG/LLM hallucinations can misstate policy — escalate sensitive topics (`escalate_to_hr`).

## What this template provides

- Server-enforced `human_review_required` and `disclaimer` on every response.
- `escalate_to_hr` field in the schema for sensitive topics.

## What operators must still implement

- Authoritative policy corpus with version control.
- Human escalation path for legal, harassment, accommodation, and termination topics.
- Access controls and audit trails for employee queries.

**For research and demo only unless you complete a full compliance programme.**
