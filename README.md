**The Certainty Standard**

An open evidentiary framework for blockchain attribution claims.

Author: Sean B. Collier · Version 1.0 · 2026

---

 ## What this is

The Certainty Standard is a disclosure framework for how blockchain attribution
claims are presented and evaluated. Most on-chain tracing evidence is delivered as a
single confidence conclusion that silently blends two very different things:

- **what the protocol forces to be true** — facts entailed by Bitcoin's rules, which
  cannot be argued away; and
- **what is inferred** — behavioral heuristics that are often reliable but are, by
  nature, defeasible.

**The Certainty Standard** requires these to be separated and labeled, and certifies only the
protocol-forced portion. Inference is disclosed as inference. Uncertainty is marked
honestly rather than absorbed into a number.

The goal is attribution evidence that is **narrower but far more defensible**: it never
claims more than the protocol guarantees, so there is less for an opposing party to
discredit.

 ## Why it exists

In contested matters, attribution evidence is routinely attacked at its weakest point —
the inferred heuristics — in order to discredit the whole conclusion, including the parts
that were actually provable. Existing forensic methods are also typically closed: the
heuristic logic is proprietary and not open to inspection by the party challenging it.

The Certainty Standard is **open and auditable by design.** It is intended as a neutral
reference that any party — including the party on the receiving end of an attribution —
can use to test what is genuinely forced versus what is merely likely.

## Classifications

- **FC+ (Forced-Control Positive)** — control is entailed by the protocol relative to a
  declared heuristic set; survives challenge.
- **FN− (Forced Non-Linkage)** — non-linkage is entailed relative to the declared set.
- **FLIP** — compliant heuristics conflict; no forced claim is issued.
- **UNDETERMINED** — no method speaks; silence is declared, not resolved.

A claim of control under this Standard is a claim about **keys / control**, never about
legal ownership of a person, and is always stated **relative to a declared heuristic set.**

## Status

This is an early-stage framework, openly documented. The Specification (this repository)
defines the disclosure rules. A reference implementation exists separately and is under
active development; it is a prototype, not a certified product. Nothing here is a certified
finding, an expert opinion, or evidence.

## The Specification

See `Certainty_Standard_v1.0_Specification.pdf` in this repository for the full framework.

## Contact

Inquiries about the Standard and its methodology: Sean B. Collier.

---

© 2026 Sean B. Collier. See `LICENSE_AND_AUTHORSHIP.md`.
