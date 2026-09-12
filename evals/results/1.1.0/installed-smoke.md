# Installed runtime smoke test

Date: 2026-09-12. A fresh agent read the installed v1.1.0 entrypoint from disk
and followed its reference routing. No eval cases or prior outputs were supplied.
The artifacts below are the returned text; local path prefixes in the loading
receipt are omitted for portability. This was a local writing test, not a send.

## Request

Give two short artifacts. First, an 80–110-word fictional scene: an elderly
caretaker, alone in a closing cinema, first uses a folded programme to prop open
a rattling door; on leaving, the caretaker retrieves the programme and pockets
it. Small actions may be invented within this premise. Let the change in the
object's use carry the ending without explaining a moral. Second, a separate
project note under 45 words: the director has approved the revised ending; tell
the editor to use that ending and deliver the export by 17:30 IST today. No
sender is specified.

## Returned artifacts

The elderly caretaker folded a programme twice and pushed it beneath the rattling door with the toe of her shoe. The door stayed open. Alone now, she went down the aisle, lifting each seat to check beneath it. At the back she found a glove and laid it on the ticket counter. She switched off the auditorium lights, then the foyer lights. At the door she bent slowly, one hand on the frame, and pulled the programme free. Outside, she locked up, brushed the grit off the programme and smoothed its crease with her thumb. She slipped it into her coat pocket.

---

The director has approved the revised ending. Please use that ending and deliver the export by 17:30 IST today.

## Readback

The agent reported reading these installed files. Parent verification confirmed
that every listed runtime file matched the final source byte-for-byte:

- `SKILL.md`
- `references/narrative-craft.md`
- `references/craft-decisions.md`
- `references/speaker-modes.md`
- `references/medium-registers.md`
- `references/rhythm-wit-warmth.md`
- `references/voice-constitution.md`

The scene is 102 words and the note 19 words.
The object changes from a door prop to something kept. The project note
attributes approval to the director and retains the export deadline. No moral,
additional person, or invented real-world decision rationale was added.
