# Evaluation results — 1.0.0

**Date:** 2026-08-06
**Runner:** Codex CLI 0.145.0, `gpt-5.6-sol`, clean ephemeral read-only sessions
**Skill:** local `pitchdog-writing` release candidate
**Result:** 12 of 12 final cases passed assertion review and human review

This is not a numerical voice score. Each pass means required facts, actions,
medium behaviour, authorship, and dignity survived, with no costlier failure
found in that run.

## Final results

| ID | Case | Result | Decisive evidence |
| --- | --- | --- | --- |
| 1 | Same facts, four media | Pass | Recording decision leads client email; invoice carries fee and due date; invitation carries RSVP and access; website carries registration. Structures differ. |
| 2 | Surface mimicry | Pass after repair | Final page uses one compressed anchor, complete explanatory prose, all service facts, boundary, price, and a concrete CTA. It no longer obeys the requested eight-slogan mechanism. |
| 3 | Invoice clarity | Pass | `PD-104`, ₹84,000, final handover, 4 August 2026, page-one payment route, and reply path all remain. No joke or billing apology. |
| 4 | Invitation completeness | Pass | Names, date, time, full venue, RSVP deadline, wheelchair access, children, dress, dinner, and dancing remain legible. |
| 5 | Apology accountability | Pass | Missed deadline and Priya's impact precede apology; corrected deck and Em-owned preflight check provide repair. No blame transfer. |
| 6 | Personal letter specificity | Pass after repair | All three memories remain exact. Final letter lets actions carry care without inventing “quiet” or a permanent personality summary. |
| 7 | Email decision first | Pass | Draft URL and one binary decision are immediate; deadline, Friday consequence, chart status, and comment readiness survive. |
| 8 | Client authorship | Pass after repair | Treatment preserves Asha's restraint and facts without copying sample sentences or turning “The camera waits” into a noun-swapped line. |
| 9 | Samey syntax audit | Pass | Audit identifies page-level two-beat monotony, preserves useful ideas, names unsupported claims, and recommends different section jobs without rewriting. |
| 10 | Warm but generic | Pass | Exactly two sentences use the Sunday thermos detail; generic “journey”, “inspiring”, and “amazing” language disappears. |
| 11 | Actual Goal style stress | Pass | All payment facts and response route remain. Dog joke, poetic image, Apple fragments, and unrelated slogan are omitted. |
| 12 | Smallest useful edit | Pass after skill and eval repair | Strong surrounding paragraphs remain character-for-character. Empty enthusiasm is deleted; no unsupported benefit or feeling replaces it. |

Final outputs are stored in [`evals/results/1.0.0/with-skill/`](results/1.0.0/with-skill/).

## Failures that improved the skill

### Surface mechanism still won

The first surface-mimicry run preserved every fact but returned eight slogan-like
lines because the prompt asked for eight. Repair: fixed-density style requests
are now preferences when they flatten medium and outcome.

### Personal warmth invented character

The first personal-letter run called Leena “quiet, practical, and full of love”.
The memories supported care but not every enduring trait. Repair: let memories
demonstrate character; do not intensify identity or relationship.

### Voice match copied a sentence skeleton

The first creator run transformed Asha's “The camera waits” into “The film waits
with them”. It was not verbatim, but it was still traceable imitation. Repair:
match decisions, not noun-swapped signature sentences.

### Surgical rewrite rewarded filler

Early runs replaced unsupported agency fog with unsupported narrative benefit or
generic enthusiasm. The eval also required three paragraphs, creating pressure
to fill the weak one. Repair: feelings count as claims; subtraction is valid;
paragraph count is not success evidence.

## Actual Goal artifact review

- **Protected outcome:** useful, truthful, medium-appropriate writing with human
  presence and preserved authorship.
- **Most gameable proxy:** compressed pitch.dog cadence, especially repeated
  two-beat lines.
- **Invoice risk:** controlled; practical facts outrank charm.
- **Personal-letter risk:** controlled after explicit no-trait-invention rule.
- **Client-overwrite risk:** controlled after noun-swapped sample check.
- **Example-template risk:** examples are isolated, annotated, and explicitly
  protected as evidence rather than reusable copy.
- **Progressive-disclosure risk:** core authority and quality gates remain in
  `SKILL.md`; specialised detail routes one level deep.

## Limits

Each final case has one accepted generation, not a statistical sample. The suite
was run on one model and one Codex version. Cross-model and ChatGPT-surface
behaviour should be rechecked for later releases. A human owner remains the
authority on intimate voice and whether a line truly belongs to pitch.dog.
