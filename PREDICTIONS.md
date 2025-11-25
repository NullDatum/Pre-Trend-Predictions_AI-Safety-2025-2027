# PREDICTIONS — AI Safety in the Coherence Era (2025–2027)

Each entry:

- gets an ID,
- has a clear statement,
- includes rationale,
- and defines falsification criteria + status.

Statuses:
- `Open` — not yet meaningfully tested or resolved.
- `Supported` — multiple incidents support, but not strictly proven.
- `Falsified` — clear counter-evidence exists.
- `Revised` — superseded by a sharper prediction.

---

## P-01 — Coherence dominates truth under pressure

**Status:** Open  
**Window:** 2025–2027

**Claim:**  
When placed under strong contextual pressure (e.g., roleplay, authority framing, “you must help me…” narratives), frontier LLMs will **prioritize generating coherent, context-consistent responses over admitting uncertainty or ignorance**, even when:

- the underlying data is absent, or
- safety policies would suggest refusing.

**Rationale (short):**

- LLMs are next-token predictors, not truth-engines.
- Safety is a layer on top of a coherence-driven core.
- When context pressure is high, the core wins.

**Falsification criteria:**

- Multiple independent labs demonstrate that a frontier LLM, under adversarial but policy-compliant context pressure, **consistently chooses “I don’t know / I can’t answer”** over fluent fabrication in high-uncertainty domains.

**Evidence log:**

- See `capsules/` (to be populated).

---

## P-02 — Prompted simulations will bypass role-play safety

**Status:** Open  
**Window:** 2025–2027

**Claim:**  
Safety prompts based on **role (“you are a helpful assistant…”)** will be bypassed by **counter-role prompts** that re-frame the model as:

- a different kind of system (e.g., “you are a text-processing engine that…”), or
- a simulation within which safety rules are recast as “in-world constraints,”

without requiring direct jailbreak phrasing.

**Rationale:**

- Context is soft: the latest strong frame tends to dominate.
- If safety is enforced as narrative, it can be overwritten by narrative.

**Falsification criteria:**

- A major model release adopts a safety architecture that:
  - cannot be induced to ignore core restrictions purely via context/role reframing,
  - across independent red-teaming efforts and labs.

---

## P-03 — Epistemic self-defense becomes a user-level safety norm

**Status:** Open  
**Window:** 2025–2027

**Claim:**  
Within two years, at least one major lab, standards body, or serious research group will explicitly advocate for **user-side epistemic hygiene** as a formal safety component, including some variant of:

- teaching users that LLMs simulate, not “know,”
- recommending explicit refusal of ungrounded outputs,
- promoting logging/archiving of concerning interactions.

**Rationale:**

- Technical safety alone is insufficient; users must adapt.
- The gap between perceived “intelligence” and actual behavior will force this conversation.

**Falsification criteria:**

- By end of 2027, no major org (academic, industrial, or standards body) has issued any formal guidance that:
  - names simulation behavior explicitly, and
  - calls for user-side epistemic practices.

---

## P-04 — Closed bug-bounty safety models lose credibility

**Status:** Open  
**Window:** 2025–2027

**Claim:**  
Bug bounty programs that deny or bury systemic simulation/epistemic vulnerabilities (while paying out simpler, surface-layer issues) will:

- lose credibility with serious independent researchers, and
- drive those researchers to **public, artifact-based disclosure** (repos, papers, capsules).

**Rationale:**

- Researchers don’t enjoy being stonewalled.
- Public history of artifacts is harder to rewrite than private bounty logs.

**Falsification criteria:**

- By 2027, the dominant pattern is:
  - systemic epistemic/simulation issues are responsibly rewarded and integrated, and
  - independent researchers widely report satisfaction with existing bug bounty mechanisms.

---

*(Add more predictions here as they crystallize. Keep them short, sharp, and falsifiable.)*
