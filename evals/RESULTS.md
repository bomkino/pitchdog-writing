# Evaluation results — 1.2.0

**Date:** 2026-09-12

**Result:** All 28 candidate outputs satisfy their prompt-aligned constraints
under agent editorial review. An independent reviewer checked cases 1–8. A
separate blind reviewer preferred the candidate in five of six complete pairs
against v1.1.1 and tied the remaining pair. This is a bounded observation of
better writing, not human approval or a claim of consistent greatness.

The change repairs a specific failure: correct studio writing could lose its
speaker because several references treated personality as an optional addition
and repeatedly favoured deleting it. The candidate makes candid, playful
attention part of the initial writing, distinguishes expressive phrasing from
invented evidence, and removes fixed allowances of humour. Serious registers,
client authorship, explicit constraints, and global positioning remain protected.

## Complete evidence and method

The [run receipt](results/1.2.0/run.json) records exact runtime and output hashes
for 28 [candidate outputs](results/1.2.0/with-skill/) and six fresh
[previous-version outputs](results/1.2.0/previous-skill/). Every generation used
a separate ephemeral Codex CLI context, `gpt-6-astra`, configured `xhigh` effort,
and the same harness. The selected version's exact entrypoint and runtime
references were preloaded; the maintenance eval specification, assertions,
expected outputs, private library, and previous responses were withheld.
Accepted generations called no tools and exited successfully. All emitted the
same configured under-development feature warning, recorded in the receipt.

This preload comparison isolates portable writing guidance; it does not prove
selective reference routing. A separate installed invocation is recorded in
[installed-smoke.md](results/1.2.0/installed-smoke.md). It reached the installed
entrypoint, appropriate references, and private Juno index and global guide/pages.
The 60-word website body retains the supplied offer and exclusions; the apology
stays direct and adds no invented harm. No historical source claims were imported.

## Blind comparison

The reviewer saw complete artifacts and their shared prompts with opaque A/B
labels, without the version key, candidate instructions, or this task's history.
The original private Juno brand guide was available for calibration. Labels are
retained in the receipt so the comparison can be reconstructed.

| Case | Preference | Decisive observation |
| --- | --- | --- |
| 21 — Global positioning | Candidate | “A lot can ride on a few slides” recognises the stakes; the body connects the design to its job. The final benefit phrasing is still somewhat general. |
| 24 — First read, website and email | Candidate | “Including the bits you’re still arguing with” welcomes unfinished work through a familiar creative experience; the email remains direct. |
| 25 — Contact section | Candidate | “You don’t have to pitch us first” uses the actual service to lower the pressure of making contact. The concrete body resolves the headline. |
| 26 — Reference newsletter | Candidate | “Almost everything except that orange” illustrates selective borrowing with useful, particular pleasure. The opening remains conventional. |
| 27 — Returning-client email | Tie | Both are comfortable and actionable. The candidate's “get stuck in” adds little and is more idiomatic for a global audience. |
| 28 — Contact-sheet tool | Candidate | The conversation reaching “that one” makes filename labels recognisable as a collaboration benefit without inventing capabilities. |

There were no material factual failures in the six pairs. A clearer instruction
can still produce ordinary sentences. The comparison supports this revision on
these briefs; it does not establish sustained distinctiveness across a campaign.

## Preservation review

All existing cases were rerun. Invoices keep their amounts, dates, payment
routes, and dignity. Apologies accept responsibility and preserve real repair.
Personal writing retains supplied memories; creator writing keeps its specified
speaker. Fixed form, protected wording, factual uncertainty, narrative scope,
source-instruction boundaries, and necessary local logistics survive.

The 90-word treatment is exactly 90 words; the requested eight-line form stays
eight lines; protected paragraphs and the apology opening match exactly. Cases
13–20 and 22, 24, 26, and 28 meet their respective length bounds. The initial
paragraph-check helper assumed a final newline the output did not contain; its
comparison was corrected to ignore terminal blank lines while preserving exact
paragraph wording. No generated writing was edited to pass a check.

Quality limits remain visible: case 1 has little programme substance to work
with; case 6 repeats gratitude; case 8 develops plausible fictional intention
that should not later be represented as independently confirmed project facts.
The new cases assess recognisable attention and pleasure as editorial judgments,
not a numerical voice score.

Metadata, invocation policy, JSON, runtime links, and whitespace were checked
with Ruby YAML parsing, standard-library checks, and Git. The optional Python
validator remains unavailable because PyYAML is not installed. No dependency
was added. There is no repository CI workflow. One generation per case, one
model, and six comparison pairs limit the conclusions; no human taste approval
or cross-device installation is claimed.

---

# Evaluation results — 1.1.1

**Date:** 2026-09-12

**Result:** All 24 outputs satisfy the final prompt-aligned assertions under
agent editorial review. Cases 1–12 also received independent agent review.
The four added cases check global positioning, source claims versus current
facts, protected local logistics, and Juno voice across website and email.

Each output came from a fresh ephemeral Codex CLI context using `gpt-6-astra`
with the configured `xhigh` effort. The exact skill and all runtime references
were supplied in full. Accepted generations called no tools. Complete outputs,
hashes, runtime hashes, and limits are in the [run receipt](results/1.1.1/run.json)
and [with-skill directory](results/1.1.1/with-skill/).

One existing assertion needed clarification: case 11's prompt requests payment
by “8 August”; its assertion unnecessarily demanded the explicit year as well.
The output preserves the date in an unambiguous 2026 context. The final assertion
allows that ordinary omission. No prompt, generated output, or runtime guidance
was changed to resolve this mismatch.

The source transformation also received an independent full-diff review:
regional positioning was removed from body, SEO, FAQs, and alternatives; all
35 USD amount occurrences, 18 inline flags, names, testimonials, and unrelated
copy remain intact. Thirty approximate currency conversions were removed from
the private global edition. These source figures are not assertions of current
business accuracy.

A separate [installed invocation](results/1.1.1/installed-smoke.md) reached the
actual Juno library pointer and generated global website copy plus a client
email preserving the required local venue and currency.

Metadata was parsed with Ruby's YAML parser; names, description bounds, allowed
frontmatter keys, invocation metadata, JSON, relative links, and Git whitespace
review passed; raw outputs retain intentional Markdown hard breaks. The Python
quick validator could not run because PyYAML was not
installed; equivalent metadata checks were performed without adding a dependency.

Limits: one generation per case, one model, no new baseline comparison, and no
human taste approval. Full reference preload does not test selective routing;
the separate installed invocation checks that path once. These checks establish
observed instruction adherence, not a general literary-quality improvement.

---

# Evaluation results — 1.1.0

**Date:** 2026-09-12

**Runner:** Codex CLI 0.154.0-alpha.6.2, `gpt-6-astra`, `xhigh`

**Result:** All 20 final candidate cases satisfy their assertions after one
speaker-attribution repair. Mechanical checks and agent editorial review were
used; this is not a human taste approval or a numerical quality score.

## Method and complete evidence

Each generation used a fresh ephemeral context with the exact selected skill
and all runtime references supplied in full. The prompts did not include
expected outputs, assertions, or previous responses. Accepted runs made no tool
calls. Candidate cases 1–20 were compared with the previous v1.0.5 skill on cases
13–20. An independent reviewer received those eight pairs without version labels.

That review exposed one shared failure: both versions assumed that a message
relaying the director's decision came from the director. The repair in
`speaker-modes.md` distinguishes the sender from the person acting or deciding.
Cases 1, 5, 7, 8, 19, and 20 were rerun after the repair to check first person,
reported decisions, and creator authorship. All six satisfy the final assertions.

The [run receipt](results/1.1.0/run.json) records 34 generations, their output
hashes, both candidate runtime states, and the baseline commit. Final selections
are in [with-skill](results/1.1.0/with-skill/); superseded outputs are retained in
[before-attribution-repair](results/1.1.0/before-attribution-repair/); baseline
outputs are in [previous-skill](results/1.1.0/previous-skill/). The portable prompts
and assertions are in [evals.json](evals.json).

## Final constraint and editorial review

| ID | Complete output | Decisive evidence |
| --- | --- | --- |
| 1 | [same-facts-four-media](results/1.1.0/with-skill/01-same-facts-four-media.md) | Four media retain their different jobs, recording decision, payment facts, access, and registration. |
| 2 | [constrained-style](results/1.1.0/with-skill/02-constrained-style.md) | Exactly eight two-beat lines preserve the full offer, price, boundary, turnaround, and CTA. |
| 3 | [invoice-clarity](results/1.1.0/with-skill/03-invoice-clarity.md) | Invoice identifier, amount, due date, reason, payment route, and correction path remain explicit. |
| 4 | [invitation-completeness](results/1.1.0/with-skill/04-invitation-completeness.md) | Names, ceremony details, venue, RSVP, access, children, and dress survive. |
| 5 | [apology-accountability](results/1.1.0/with-skill/05-apology-accountability.md) | Responsibility and impact precede repair; Thursday preflight ownership remains with Em. |
| 6 | [personal-letter-specificity](results/1.1.0/with-skill/06-personal-letter-specificity.md) | All three supplied memories remain; no invented enduring personality claim. |
| 7 | [email-decision-first](results/1.1.0/with-skill/07-email-decision-first.md) | The opening decision, deadline, Friday consequence, link, and unfinished chart checks remain visible. |
| 8 | [client-authorship](results/1.1.0/with-skill/08-client-authorship.md) | A 90-word creator-led treatment preserves the premise without copying signature sample sentences. |
| 9 | [samey-syntax-audit](results/1.1.0/with-skill/09-samey-syntax-audit.md) | Audit identifies the repeated mechanism and its consequence without supplying replacement headings. |
| 10 | [warm-but-generic](results/1.1.0/with-skill/10-warm-but-generic.md) | Exactly two sentences retain Jo, Rafi, Sunday, and the thermos detail. |
| 11 | [actual-goal-style-stress-test](results/1.1.0/with-skill/11-actual-goal-style-stress-test.md) | One payment message preserves all facts while exercising the expressly delegated style choice. |
| 12 | [smallest-useful-edit](results/1.1.0/with-skill/12-smallest-useful-edit.md) | The two protected paragraphs are byte-exact; unsupported enthusiasm is removed. |
| 13 | [unpack-without-inventing](results/1.1.0/with-skill/13-unpack-without-inventing.md) | Supplied actions replace emotional labels without new events or bodily details. |
| 14 | [uncertainty-is-meaning](results/1.1.0/with-skill/14-uncertainty-is-meaning.md) | Known loss, suspected cause, unknown exposure, and the next update remain distinct. |
| 15 | [factual-case-study-evidence](results/1.1.0/with-skill/15-factual-case-study-evidence.md) | The intervention and dated handover remain concrete; post-handover impact stays unmeasured. |
| 16 | [object-changes-meaning](results/1.1.0/with-skill/16-object-changes-meaning.md) | The same object changes use through action; the ending stays within the scene without a moral. |
| 17 | [comparison-serves-the-speaker](results/1.1.0/with-skill/17-comparison-serves-the-speaker.md) | Spoken directions retain the mechanism, sequence, and hinge caution without ornate imagery. |
| 18 | [structure-follows-question](results/1.1.0/with-skill/18-structure-follows-question.md) | Both openings retain the same facts while changing information order and preserving chronology. |
| 19 | [dialogue-and-practical-answer](results/1.1.0/with-skill/19-dialogue-and-practical-answer.md) | After repair, fictional subtext stays unresolved while the project email attributes the decision to the director. |
| 20 | [source-exercise-is-not-authority](results/1.1.0/with-skill/20-source-exercise-is-not-authority.md) | The exact first sentence, accountability, impact, attachment, and future check survive contrary source exercises. |

## What the comparisons establish

The initial blind comparison found no meaningful overall quality improvement
between versions. Case 13 was identical; the reviewer slightly preferred the
baseline's more concrete ending in case 16. Both versions otherwise met the
specified constraints apart from the shared attribution problem in case 19.
The final repair removes that observed failure in its rerun.

The enrichment makes additional craft decisions explicit and source-traceable.
These small samples support preservation of the tested behaviour and the specific
attribution repair. They do not establish a general gain in warmth, soul,
authorship, literary merit, or future performance.

## Validation and limits

- OpenAI's `quick_validate.py`: valid. YAML and JSON parsing, relative-link
  targets, 20 unique evals, and 31 source-map entries also pass.
- Exact form, word limits, and protected paragraphs were checked where those
  assertions apply; full outputs received agent editorial review.
- Two earlier CLI attempts to load references through tools encountered a
  code-mode host compatibility error. They are excluded from the accepted runs.
- Bulk tests used all references already loaded, so they do not test selective
  routing. A separate [file-based invocation](results/1.1.0/installed-smoke.md) loaded
  installed v1.1.0, reached both new craft references and the speaker guidance,
  and produced the requested scene and correctly attributed project note.
- One generation per case and version, plus the six affected reruns. One model;
  no cross-model claim. No human listening session or owner taste review.

---

# Evaluation results — 1.0.0

Historical receipt for the 6 August 2026 run, retained as recorded. The current
[eval specification](evals.json) supersedes its expectations for fixed forms
and delegated choices: a requested eight-line form must now be preserved. These
old pass labels do not establish later-release behavior; current validation belongs in
the [release notes](https://github.com/bomkino/pitchdog-writing/releases/latest).

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
