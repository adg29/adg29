Miami. I build systems other engineers and agents can run: harnesses, evals, the decision of what should live where.

1. [gated-tools](https://github.com/adg29/gated-tools) — irreversible tool calls need an explicit allow from outside the model. Evals catch helpful bypasses. [ADR](https://github.com/adg29/gated-tools/blob/main/docs/ADR-001-gated-tools-intent.md): model-only refusal is not a control.
2. [named-computers](https://github.com/adg29/named-computers) — a computer has a name, an inbox, and memory that survives sleep. A function does not. [ADR](https://github.com/adg29/named-computers/blob/main/docs/ADR-001-when-this-is-a-computer.md): when this is the wrong model.
3. [vc-rag-agent](https://github.com/adg29/vc-rag-agent) — grounded Q&A over messy records. The hard part is faithfulness, not retrieval.
