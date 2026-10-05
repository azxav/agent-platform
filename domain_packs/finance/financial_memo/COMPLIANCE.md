# financial_memo — sample / demo only

This pack is a **portfolio sample**. It drafts a short SCQA-style memo from whatever text you pass in.

It is **not**:

- financial, investment, credit, or trading advice
- a bank, MiFID, SEC, or FINRA control
- a production compliance product

The server overwrites `disclaimer` and sets `human_review_required: true` on every response so the model cannot drop that label. Output integrity checks still run.

`financial_memo` is **runnable** with `LLM_PROVIDER=mock` and does **not** sit behind `REGULATED_PACKS_ENABLED`. HR and legal packs do, and they stay disabled.

Do not point this route at real customer money, positions, or confidential deal data.
