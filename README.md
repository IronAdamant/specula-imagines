# Specula imagines: reference pictures

> **Adults only (18+) for one folder.** [`ADULTS-ONLY/`](ADULTS-ONLY/README.md) holds 24 unclothed
> anatomical plates and motion studies from the 18th and 19th centuries (Albinus, Richer, Muybridge
> and a sculpted muscle figure). They show the whole body, genitals included, because that is how
> anatomy and gait were recorded. Nothing here is sexual. Everything outside that folder is skeletons,
> parts of the body, heads, and animals.

110 pictures that the figures and creatures of the [Specula](https://github.com/IronAdamant/Specula)
game engine are held against while they are built: anatomical plates, skeletons, muscle figures,
studies of people and animals in motion, and skeletons of animals by body plan. Every one is in the
public domain or under a Creative Commons licence that allows this, and every one has its source,
its author and its licence in [INDEX.md](INDEX.md).

## Why this exists

Specula builds its people and animals by code, from published measurements (a survey of 6,068
people for the human body). Measurements say how long and how wide; they do not say what a shoulder
looks like. The engine's owner, on why the pictures were gathered (2026-11-17):

> "it's how human artists, in any profession, work. They refer to skeleton images before putting in
> their touches... Even though they know what humans look like, they still use reference and
> measurements, so I'm getting you digital equivalent of those."

The measurements are in Specula, under
[`docs/research/library/`](https://github.com/IronAdamant/Specula/tree/main/docs/research/library)
(45 topics, each number with its source). This repository is the other half: something to look at.
The list it was gathered from is Specula's `docs/research/REFERENCE_IMAGES_BRIEF.md`, and the figure
being built against it is described in Specula's `docs/design/FIGURE.md`.

## The rule

**The pictures are looked at and compared. They are never traced, and no picture's pixels go into an
asset or ship with the engine.** A capture of the engine's figure is put beside a plate, and what
differs is written down and mended in the figure's own numbers.

## What is here

| Folder | Pictures | What |
|---|---|---|
| `1-whole-body/` | 17 | Skeletons front, side and back (Albinus, Vesalius, Richer), a woman's skeleton, labelled diagrams, the trunk's muscles |
| `2-weak-areas/` | 24 | Neck and shoulders, hands, feet, knees, elbows, the pelvis of each sex: bones and muscles |
| `3-head/` | 8 | Skulls in several views, a living head front, side and three-quarter, the head's muscles |
| `4-motion/` | 6 | Muybridge: a horse walking and galloping, a dog and a cat galloping, an elk walking, a draped woman walking |
| `5-creatures/` | 31 | A skeleton and other views for each body plan: dog, lion, horse, cow, goat, deer, bear, elephant, ostrich, bat, pterosaur, lizard, crocodile, snake |
| `ADULTS-ONLY/1-whole-body/` | 16 | Whole unclothed figures, living and as muscle figures, front, side and back; a proportion canon |
| `ADULTS-ONLY/2-weak-areas/` | 3 | The hips from the front and the side; the shoulders on a whole figure |
| `ADULTS-ONLY/4-motion/` | 5 | Muybridge: men and women walking and running, unclothed |

**Missing**, by the index's own account: fish, spiders and insects; a woman's whole figure from the
side, and women generally beside the men; a whole figure at three-quarter; slender and heavy builds;
a range of ages. [INDEX.md](INDEX.md) says how well each kind is covered and lists three pictures
that were found and not taken, with the reason.

## Sources and licences

All 110 files come from Wikimedia Commons. **88 are in the public domain, 3 are CC0, and 19 are
CC BY** (18 under CC BY 4.0, one under CC BY 2.0). None is non-commercial or no-derivatives.

[INDEX.md](INDEX.md) has a row for every picture: the file, what it shows, the view, the subject, the
Commons page it came from with its author or collection and year, the licence with the link that
states it, and the date it was checked (2026-11-17). Licence, author and size were read from the
Commons record for each file, not guessed.

- **If you reuse a CC BY picture, credit it as its row in the index does** (author, source, licence).
- **Changes made to the files:** where an original was larger than 2,500 pixels on its long side, the
  file here is Commons' own 2,500-pixel render of it; four diagrams are 2,500-pixel renders of
  public-domain SVGs. Nothing else was altered. The index gives each saved file's size in pixels.
- Every picture keeps the licence in its row.

The set was gathered and indexed by Grok at the owner's request, and placed here by Claude, who also
moved the 24 unclothed pictures under `ADULTS-ONLY/` and changed their paths in the index to match.

**If a row is wrong** (a licence, an author, a source), please open an issue: the picture will be
corrected or removed.

## Using it with Specula

Clone it anywhere; Specula does not depend on it and never reads it. It is for whoever builds a
figure, a face, a gait or a creature, person or agent, to look at beside the engine's own captures.
