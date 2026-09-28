# pitch.dog Writing

A portable Agent Skill for writing that feels naturally written by pitch.dog,
bomkino, or a named member of the team—without turning every email, invoice,
invitation, apology, proposal, or letter into website copy.

> **Do the real job. Sound like us doing it.**

The skill follows the requested form, length, protected wording, and edit scope.
Within that brief, it protects clarity, truth, authorship, medium, relationship,
and human attention. Studio writing begins candid, interested, and playful;
personality belongs in the thought and phrasing. Serious writing stays exact
and dignified. Politics appears through credit, consent, labour, ownership,
privacy, access, dignity, and boundaries—not a values paragraph bolted onto the
work.

## What it handles

- emails and letters;
- invoices and payment notes;
- wedding and event invitations;
- proposals, estimates, and handovers;
- our own decks, and presenting work to clients;
- case studies told true;
- website, product, programme, and campaign copy;
- announcements and social posts;
- internal notes, forms, errors, and microcopy;
- apologies, personal messages, and sensitive writing;
- writing for clients and creators without stealing their voice.

The craft comes from [craft-essays](https://github.com/bomkino/craft-essays),
our open skill of Chuck Palahniuk's writing moves: unpack, received text,
horses, the buried gun, big voice and little voice. pitch.dog Writing is the
voice on top of that craft: who is speaking, what the medium must do, and how
we sound doing it. Install both. The
[source manifest](provenance/SOURCE-MANIFEST.md) records lineage and boundaries.

## What it refuses to become

Not a phrase bank. Not an Apple slogan generator. Not generic “premium” agency
copy in shorter sentences. Not dog puns. Not compulsory wit. Not a numerical
humanity score.

## Install

pitch.dog Writing 2.0 builds on
[craft-essays](https://github.com/bomkino/craft-essays) 0.2.0 or later: install
craft-essays the same way first. Keep one copy of each skill per app; two
copies of one skill drift apart.

### Claude

**Claude apps (web and desktop).** Download
[`pitchdog-writing.zip`](https://github.com/bomkino/pitchdog-writing/releases/latest/download/pitchdog-writing.zip)
from the [latest release](https://github.com/bomkino/pitchdog-writing/releases/latest).
Open **Customize → Skills**, choose **+ → Create skill → Upload a skill**, and
select the ZIP. To update, delete the older version there first, then upload
the new one. In the desktop app, uploaded skills are also available in the
Code tab.

**Claude Code in a terminal:**

```bash
npx skills add bomkino/pitchdog-writing --agent claude-code --global
```

Or extract the release ZIP into `~/.claude/skills/`.

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

For a fixed release, add `--branch v2.0.0 --depth 1` to the clone. Or install
only for one repository:

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
├── references/          # voice, registers, speakers, modes; loaded when needed
├── evals/evals.json     # portable test cases
├── docs/                # maintainer handover
└── provenance/          # source lineage and decisions
```

## Contribute

Issues and pull requests are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md)
before changing the voice reference or calibration evidence. Examples should
teach judgment, not become templates.

No contributor licence agreement. No attribution requirement.

## Licence

[0BSD](LICENSE): use, copy, change, distribute, bundle, or sell it for any
purpose, with or without attribution.

The licence grants broad rights to the work. It does not imply endorsement by
pitch.dog of a modified version or someone else's output.
