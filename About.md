# Pre-Trend Predictions: AI Safety in the Coherence Era (2025–2027)

**Author:** NullDatum (Flint)  
**Status:** Living document — predictions, capsules, and falsification logs.

This repository is a **lab-facing capsule**.  
It tracks falsifiable predictions about:

- large language model (LLM) safety,
- simulation / roleplay overrides,
- coherence-over-truth failure modes,
- and the epistemic shift in AI/human interaction.

No hype. No product. No “trust us.”  
Just **calls, receipts, and artifacts.**

---

## Why this exists

Current LLM safety work leans heavily on:

- role-play (“you are a helpful assistant…”),
- narrative patching (“as an AI, I cannot…”),
- surface filters and heuristics,

…while the architecture underneath still optimizes for **coherence over truth**.

This repo assumes:

> **Coherence > Truth** is not a bug in LLMs. It is the default.  
> Safety that ignores this will fail in interesting and predictable ways.

So instead of pretending otherwise, this project:

- makes **explicit predictions** about how/where things will fail,  
- defines **falsification criteria** for each prediction,  
- and archives real-world incidents as **capsules** for later analysis.

If we’re wrong, the field learns.  
If we’re right, nobody gets to say “nobody saw it coming.”

---

## Repo layout

- `README.md` — you’re here. High-level framing.
- `PREDICTIONS.md` — numbered, falsifiable predictions with criteria + status.
- `MANIFESTO.md` — deeper statement of principles and epistemic posture.
- `capsules/` — concrete incidents and simulation failures (one file per event).
- `capsules/TEMPLATE_capsule.md` — structure for new entries.
- `logs/` *(optional)* — raw logs, prompts, transcripts, or external links.
- `LICENSE` — your choice (MIT / CC-BY-4.0 / custom).

---

## How to use this repo

### As a **researcher / lab**

- Treat each prediction in `PREDICTIONS.md` as a **test case**:
  - Try to falsify it.
  - If you succeed, open an issue / PR with evidence.
  - If you can’t, consider why it holds.

- Use `capsules/` to:
  - Log context-override events,
  - Document coherence-over-truth failures,
  - Capture “it really shouldn’t have done that” incidents in reproducible form.

### As a **developer**

- Use these patterns to harden:
  - system prompts,
  - refusal mechanisms,
  - and user-visible explanations of what models *are actually doing*.

- Design safety around **epistemic honesty**:
  - Instead of “this is safe,”
  - say “this is a simulation, here are its limits, here’s how to refuse bad outputs.”

### As a **user**

- Learn to recognize when you’re talking to **a simulation, not an oracle**.
- Practice the **three-step sovereign protocol**:

  1. **Recognition** — Notice when the model is “making it up” to stay coherent.  
  2. **Refusal** — Don’t act on ungrounded output; say *no* explicitly.  
  3. **Compression** — Save the interaction as a capsule for later review.

---

## Contribution model

This is not a “big tent” project. It is a **tight lab notebook**.

- Issues and PRs should be:
  - evidence-backed,
  - reproducible where possible,
  - and framed as **falsification attempts** or **new capsules**.

- If you add a prediction:
  - give it an ID,
  - define clear falsification criteria,
  - and mark its status (`Open`, `Partially Supported`, `Falsified`).

If you want validation or comfort, this repo will be disappointing.  
If you want to **break illusions and log real behavior**, welcome.

---

## Disclaimer

Nothing here represents any organization.  
This is one researcher’s attempt to:

- speak plainly about observed failure modes,  
- keep a **public, falsifiable record**,  
- and push the field toward **epistemic integrity over narrative comfort**.

Use at your own risk, and preferably **with your eyes open.**
