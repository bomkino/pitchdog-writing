# pitch.dog Writing

A portable Agent Skill for writing that feels naturally written by pitch.dog,
bomkino, or a named member of the team—without turning every email, invoice,
invitation, apology, proposal, or letter into website copy.

> **Do the real job. Sound like us doing it.**

The skill follows the requested form, length, protected wording, and edit scope.
Within that brief, it protects clarity, truth, authorship, medium, relationship,
and human attention before visible style. Wit is optional. Warmth is attention, not
enthusiasm. Politics appears through credit, consent, labour, ownership,
privacy, access, dignity, and boundaries—not a values paragraph bolted onto the
work.

## What it handles

- emails and letters;
- invoices and payment notes;
- wedding and event invitations;
- proposals, estimates, and handovers;
- website, product, programme, and campaign copy;
- announcements and social posts;
- internal notes, forms, errors, and microcopy;
- apologies, personal messages, and sensitive writing;
- writing for clients and creators without stealing their voice.

## What it refuses to become

Not a phrase bank. Not an Apple slogan generator. Not generic “premium” agency
copy in shorter sentences. Not dog puns. Not compulsory wit. Not a numerical
humanity score.

## Install

### ChatGPT

1. Download [`pitchdog-writing.zip`](https://github.com/bomkino/pitchdog-writing/releases/latest/download/pitchdog-writing.zip) from the [latest release](https://github.com/bomkino/pitchdog-writing/releases/latest), which also includes `SHA256SUMS`.
2. Open **Plugins → Skills → Create → Upload from your computer**.
3. Upload the archive, review the scan, and install the skill.

Availability, installation, and syncing vary by product, surface, and workspace
settings. Confirm the skill is available in the client you intend to use. See
[OpenAI’s Skills guide](https://help.openai.com/en/articles/20001066).

### Codex and other Agent Skills clients

Install for the current user:

```bash
git clone https://github.com/bomkino/pitchdog-writing.git ~/.agents/skills/pitchdog-writing
```

Or install only for one repository:

```bash
git clone https://github.com/bomkino/pitchdog-writing.git .agents/skills/pitchdog-writing
```

If your client uses a different skills directory, place the repository there.
The package follows the open [Agent Skills specification](https://agentskills.io/specification).

## Use

Invoke it explicitly:

```text
Use $pitchdog-writing to rewrite this email. Keep the decision in the first paragraph.
```

```text
Use $pitchdog-writing in Sensitive mode. Apologise without defending us.
```

```text
Use $pitchdog-writing to audit this invitation. Do not rewrite it yet.
```

```text
Use $pitchdog-writing to voice-match these three samples for a personal letter.
```

Supported modes: Write, Rewrite, Distil, Warm, Wit, Voice Match, Audit,
Options, and Sensitive.

## Package map

```text
pitchdog-writing/
├── SKILL.md
├── agents/openai.yaml
├── references/          # loaded only when the task needs them
├── evals/evals.json     # portable test cases
├── docs/                # maintainer handover
└── provenance/          # source lineage and decisions
```

## Contribute

Issues and pull requests are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md)
before changing the voice constitution or calibration evidence. Examples should
teach judgment, not become templates.

No contributor licence agreement. No attribution requirement.

## Licence

[0BSD](LICENSE): use, copy, change, distribute, bundle, or sell it for any
purpose, with or without attribution.

The licence grants broad rights to the work. It does not imply endorsement by
pitch.dog of a modified version or someone else's output.
