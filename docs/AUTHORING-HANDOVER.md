# Authoring handover

## Shipping authority

This repository is the public shipping authority for `pitchdog-writing`.
The original “Written by Us” v2.0 source remains provenance, not a runtime
dependency.

## Deliberate decisions

- **Package name:** `pitchdog-writing` satisfies the Agent Skills naming rules
  and matches the public repository. Human title: **pitch.dog Writing**.
  “Written by Us” remains the emotional and editorial title.
- **Invocation:** explicit by default. Repository ownership alone should not
  silently colour unrelated writing.
- **Progressive disclosure:** `SKILL.md` carries the operating spine. Medium,
  tonal, rewrite, anti-pattern, example, and eval detail loads only when needed.
- **No scripts:** the skill performs no computation and needs no executable
  helper. Mechanical package validation belongs in release tooling, not runtime.
- **No voice score:** soul, warmth, wit, poetry, Apple-likeness, and “human” are
  judgments, not honest numbers.
- **Examples:** protected calibration evidence, never a phrase bank.
- **Client authorship:** client and creator voice outranks the studio voice.
- **Apple influence:** purpose, agency, simplicity, craft, and restraint—not
  slogan syntax.
- **Licence:** 0BSD. OSI-approved, commercial use allowed, modification allowed,
  redistribution allowed, no attribution required.

## Known compromise

A comprehensive writing constitution can become too large to activate cheaply.
The package therefore keeps the full conceptual range while routing specialised
detail into focused references. A maintainer should remove duplication before
adding new rules.

## Release checklist

1. Validate the package with `skills-ref validate "$(pwd)"`.
2. Confirm frontmatter name matches the `pitchdog-writing` directory.
3. Confirm description is under 1,024 characters and says when to trigger.
4. Confirm every relative link resolves one level from `SKILL.md`.
5. Parse `agents/openai.yaml` and `evals/evals.json`.
6. Run the eight core media/authorship cases and the four adversarial cases.
7. Review outputs for actual outcome, medium, speaker, client authorship,
   specificity, and mechanism repetition.
8. Build an archive with `pitchdog-writing/` as its top-level directory.
9. Install and invoke the archive on each target product surface.
10. Tag the exact commit and attach the verified archive to the release.

## Acceptance statement

The package is acceptable when it can write a payment reminder, client email,
invitation, personal letter, website opening, apology, handover, and creator-led
treatment—and each still behaves like itself.

> The skill preserves how we care. It never repeats how we phrased it last time.
