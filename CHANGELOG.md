# Changelog

All notable changes are recorded here.

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
