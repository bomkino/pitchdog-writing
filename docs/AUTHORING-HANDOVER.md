# Authoring handover

## Shipping authority

This repository is the public shipping authority for `pitchdog-writing`.
The original “Written by Us” v2.0 source remains provenance, not a runtime
dependency.

Juno's global edition is the user-selected studio voice calibration. The full
master stays in the private writing library; `references/juno-voice.md` carries
portable decisions. Written by Us remains the operating contract and the craft
study remains a toolbox. Public repository changes do not publish the private
source or establish that its business claims are current.

## Deliberate decisions

- **Package name:** `pitchdog-writing` satisfies the Agent Skills naming rules
  and matches the public repository. Human title: **pitch.dog Writing**.
  “Written by Us” remains the emotional and editorial title.
- **Invocation:** explicit calls and matching voice requests may activate the
  skill. Metadata permits automatic discovery; the brief must still call for
  pitch.dog or bomkino voice. Repository ownership alone does not do that.
- **Explicit constraints:** preserve requested form, count, wording, and edit
  scope. Infer the communication goal within those constraints; vary choices
  only when the user delegates them.
- **Craft dependency:** from 2.0.0, writing craft lives in the craft-essays
  skill, the single home for the Palahniuk adaptation across our skills. This
  skill is the voice layer: speaker, medium, truth and how pitch.dog sounds.
  Install both; if craft-essays is missing, the skill says so and continues.
- **Progressive disclosure:** `SKILL.md` carries the operating spine. Voice,
  medium registers, speakers, modes and audits, examples and eval detail load
  only when needed.
- **No scripts:** the skill performs no computation and needs no executable
  helper. Mechanical package validation belongs in release tooling, not runtime.
- **No voice score:** soul, warmth, wit, poetry, Apple-likeness, and “human” are
  judgments, not honest numbers.
- **Examples:** protected calibration evidence, never a phrase bank.
- **Studio presence:** candour, play, and viewpoint shape the writing from the
  start. A factually complete studio draft can still fail by removing its speaker.
  Compare expressive and plain versions for pleasure and usefulness together.
- **Client authorship:** client and creator voice outranks the studio voice.
- **Apple influence:** purpose, agency, simplicity, craft, and restraint—not
  slogan syntax.
- **Licence:** 0BSD. OSI-approved, commercial use allowed, modification allowed,
  redistribution allowed, no attribution required.

## Known compromise

A comprehensive writing constitution can become too large to activate cheaply.
The package therefore keeps the full conceptual range while routing specialised
detail into focused references. Each meaning has one home: craft in
craft-essays, voice in `juno-voice.md`, media in `medium-registers.md`, audit
signals in `rewrite-workflows.md`. A maintainer should remove duplication
before adding new rules.

## Release checklist

1. Validate with an available Agent Skills validator, such as
   `skills-ref validate "$(pwd)"` or OpenAI’s `quick_validate.py`. Record the
   validator and result; a missing optional helper is not a package failure.
2. Confirm frontmatter name matches the `pitchdog-writing` directory.
3. Confirm description is under 1,024 characters and says when to trigger.
4. Confirm every relative link resolves one level from `SKILL.md`.
5. Parse `agents/openai.yaml` and `evals/evals.json`.
6. Run the evaluation cases that can expose failure in the changed behavior.
   Broader changes to voice, authorship, or routing warrant the full suite.
   Record prompts, outputs, findings, and cases not rerun.
7. Review those outputs for factual accuracy, requested constraints, medium,
   speaker, client authorship, specificity, and mechanism repetition.
8. Tag the exact release commit, then build the archive from that tag with
   `pitchdog-writing/` as its top-level directory:
   `git archive --format=zip --prefix=pitchdog-writing/ -o pitchdog-writing.zip vX.Y.Z`,
   then `shasum -a 256 pitchdog-writing.zip > SHA256SUMS`. The same tag always
   yields the same bytes.
9. Re-extract and validate the archive. If claiming installation on a product
   surface, verify installation and invocation there separately. A GitHub
   release alone does not make that installation claim.
10. Push the tag and attach the verified archive and `SHA256SUMS` to the
    release.

## Acceptance statement

The package is acceptable when it can write a payment reminder, client email,
invitation, personal letter, website opening, apology, handover, and creator-led
treatment—and each still behaves like itself.

> The skill preserves how we care. It never repeats how we phrased it last time.
