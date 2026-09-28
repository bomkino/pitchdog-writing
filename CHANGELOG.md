# Changelog

All notable changes are recorded here.

## 2.0.0 — 2026-09-28

**Breaking:** requires [craft-essays](https://github.com/bomkino/craft-essays)
0.2.0 or later, installed alongside. Without it, the skill says so and works
from its own references.

- Builds on the craft-essays skill for writing craft. The Palahniuk
  adaptations formerly kept in `craft-decisions.md` and `narrative-craft.md`
  now live in craft-essays, so the craft has one home across our skills.
- Merges the voice constitution, rhythm and wit guidance and Juno calibration
  into one voice reference, and the anti-patterns into the audit section of
  the modes reference. Its own runtime text shrinks from about 12,200 to 7,400 words
  (excluding the maintainer eval specification) with the tested rules preserved.
- Adds registers for our own decks, presenting work to clients, case studies
  and newsletters, with three new eval cases.
- States rules as target behaviour where a prohibition was doing the work, and
  keeps detection lists inside the audit branch.
- Restores and sharpens body voice after blind comparison: choose an angle, let
  the thought develop, and carry one line only this subject could have. Subject
  lines carry status; addressees come only from the brief.
- Records blind two-judge comparisons against 1.2.0 in `evals/RESULTS.md` and
  `evals/results/2.0.0/`.
- Adds Claude install steps and fixed-release links to the README, and the
  reproducible archive command to the release checklist.

## 1.2.0 — 2026-09-12

- Makes candid, playful studio personality part of the initial writing, with
  recognisable observations and a point of view throughout the piece.
- Removes repeated joke quotas and the default preference for stripping style;
  compares expressive and plain phrasing for timing, pleasure, and usefulness.
- Distinguishes imaginative phrasing from invented evidence while preserving
  factual claims, personal history, client authorship, and serious registers.
- Adds realistic contact, newsletter, client-email, and tool-announcement cases,
  including comparison with the previous release.

## 1.1.1 — 2026-09-12

- Makes the user-selected Juno master the primary studio voice calibration,
  with a private library pointer and portable writing decisions.
- Establishes global studio positioning while preserving real currencies,
  locations, quotations, and creator identity when required by the brief.
- Separates historical master copy from current facts, prices, and permissions.

## 1.1.0 — 2026-09-12

- Adds source-grounded craft decisions for evidence, selected detail, viewpoint,
  precise comparisons, information variety, and spoken revision.
- Adds conditional narrative guidance for structure, passage purpose, recurring
  objects, setup and payoff, duration, dialogue, and endings.
- Records the full supplied Palahniuk collection study and its limits while
  preserving Written by Us as the voice authority and keeping source prose out
  of the package.
- Extends behavioural cases to cover craft transfer, factual restraint,
  uncertainty, source-instruction boundaries, and useful narrative development.
- Separates a reported decision-maker from an unspecified message sender after
  comparison review exposed first-person misattribution.

## 1.0.5 — 2026-09-08

- Honors explicit output form, count, protected wording, and edit scope before
  inferred communication goals or voice preferences.
- Aligns the entrypoint, voice references, and evaluation cases on improving
  writing within the brief and recognizing expressly delegated choices.
- Narrows the description to the intended pitch.dog and bomkino voice requests.
- Aligns maintainer guidance, installation links, and historical evaluation
  labels with the current instructions and release evidence.

## 1.0.4 — 2026-08-06

- Allows ChatGPT and Codex to activate the skill when a request matches its
  metadata, fixing cross-surface invocation after installation.
- Keeps the stricter invocation gate inside `SKILL.md`, so ordinary unrelated
  writing still does not inherit pitch.dog voice.

## 1.0.3 — 2026-08-06

- Corrects the remaining validator commands in the pull-request checklist and
  authoring handover.

## 1.0.2 — 2026-08-06

- States ChatGPT's separate desktop and web/mobile Personal Skill installation
  requirement precisely.
- Uses an absolute path in the contributor validation command, matching the
  current reference validator's directory-name check.

## 1.0.1 — 2026-08-06

- Removes the unsupported `api` product value from `agents/openai.yaml` so
  Codex accepts the package metadata during skill discovery.
- Leaves the writing instructions and evaluated behaviour unchanged.

## 1.0.0 — 2026-08-06

- First public release of `pitchdog-writing`.
- Replaces the retired `write-like-pitchdog` skill.
- Expands the work beyond website and studio copy to personal, practical,
  commercial, celebratory, and sensitive writing.
- Makes actual outcome, medium, speaker, recipient, and relationship outrank
  surface voice cues.
- Adds explicit output modes, progressive-disclosure references, and 12 evals.
- Releases the complete package under the no-attribution 0BSD licence.
