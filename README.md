# Specula imagines: reference pictures

> **Adults only (18+) for one folder.** [`ADULTS-ONLY/`](ADULTS-ONLY/README.md) holds 56 unclothed
> anatomical plates, figure studies and motion studies from the 16th to the 19th century (Dürer,
> Albinus, Richer, Stratz, Vanderpoel, Muybridge and a sculpted muscle figure). They show the whole
> body, genitals included, because that is how anatomy and gait were recorded. Nothing here is sexual,
> and no picture of an unclothed child is in this repository at all. Everything outside that folder is skeletons, parts of the body,
> heads and faces, clothed or draped figures, animals, and drawings for 2D work.

269 pictures that the figures and creatures of the [Specula](https://github.com/IronAdamant/Specula)
game engine are held against while they are built: anatomical plates, skeletons, muscle figures,
studies of people and animals in motion, faces and their expressions, skeletons of animals by body
plan, and model sheets for 2D. Every one is in the public domain or under a Creative Commons licence
that allows this, and every one has its source, its author and its licence in an index:
[INDEX.md](INDEX.md) for the first 110 and [INDEX-round-2.md](INDEX-round-2.md) for the 159 that
followed.

## Why this exists

Specula builds its people and animals by code, from published measurements (a survey of 6,068
people for the human body). Measurements say how long and how wide; they do not say what a shoulder
looks like. The engine's owner, on why the pictures were gathered (2026-11-17):

> "it's how human artists, in any profession, work. They refer to skeleton images before putting in
> their touches... Even though they know what humans look like, they still use reference and
> measurements, so I'm getting you digital equivalent of those."

The measurements are in Specula, under
[`docs/research/library/`](https://github.com/IronAdamant/Specula/tree/main/docs/research/library)
(each number with its source). This repository is the other half: something to look at. The lists it
was gathered from are Specula's `docs/research/REFERENCE_IMAGES_BRIEF.md` and
`docs/research/REFERENCE_ROUND2_BRIEF.md`, and the figure being built against it is described in
Specula's `docs/design/FIGURE.md`.

## The rule

**The pictures are looked at and compared. They are never traced, and no picture's pixels go into an
asset or ship with the engine.** A capture of the engine's figure is put beside a plate, and what
differs is written down and mended in the figure's own numbers.

## What is here

| Folder | Pictures | What |
|---|---|---|
| `1-whole-body/` | 20 | Skeletons front, side and back (Albinus, Vesalius, Richer, Stratz), a woman's skeleton beside a man's, labelled diagrams, the trunk's muscles |
| `2-weak-areas/` | 45 | Neck and shoulders, hands, feet, knees, elbows, the pelvis of each sex: bones, ligaments and muscles (Albinus, Richer, Sobotta); hands at work (Muybridge); the forearm turning |
| `3-head/` | 29 | Skulls in several views, a living head front, side and three-quarter, the head's muscles, the head's proportions (Dürer), expressions (Darwin, Duchenne, Le Brun) |
| `4-motion/` | 43 | Muybridge: clothed or draped people on stairs, lifting and sitting; horses, oxen, goats, deer, dogs, cats, a lion, an elephant, camels, a kangaroo, baboons; pigeons, an eagle, a vulture, ostriches |
| `5-creatures/` | 61 | A skeleton and other views for each body plan: dog, lion, horse, cow, goat, deer, bear, elephant, ostrich and other birds, bat, pterosaur, lizard, crocodile, snake, fish, insects, spiders |
| `6-2d/` | 15 | Walk-cycle key poses, turnaround and model sheets, jointed and cut-out figures |
| `ADULTS-ONLY/1-whole-body/` | 28 | Whole unclothed figures of men and women, living and as muscle figures, front, side and back; two builds side by side; a proportion canon |
| `ADULTS-ONLY/2-weak-areas/` | 3 | The hips from the front and the side; the shoulders on a whole figure |
| `ADULTS-ONLY/4-motion/` | 25 | Muybridge: men and women walking, running, jumping, climbing, carrying and rising, unclothed or in a loincloth |

**Still missing**, by the indexes' own account: matched front, side and back sets of slender, muscular
and older bodies; a whole figure at three-quarter; a large open sheet of a walk cycle's key poses.
Each index says how well each kind is covered and lists what was found and not taken, with the reason.
**No unclothed figure of a child is here, drawn or photographed.** Plates of unclothed children were
left out when the sets were gathered, and a chart of proportions by age (doll-like figures with no
clothes drawn on them) and one drawing whose subjects could not be shown to be adults were taken out
when the second set was placed, and are not kept here in any form. The only children pictured are
clothed: the faces of infants and children in Darwin's plates of expressions (1872).

## Sources and licences

All 269 files come from Wikimedia Commons. **200 are in the public domain, 31 are CC0, 30 are CC BY**
(23 under 4.0, six under 3.0, one under 2.0) **and 8 are CC BY-SA** (five under 4.0, three under 3.0).
None is non-commercial or no-derivatives.

Each index has a row for every picture: the file, what it shows, the view, the subject, the Commons
page it came from with its author or collection and year, the licence with the link that states it,
and the date it was checked (2026-11-17). Licence, author and size were read from the Commons record
for each file, not guessed.

- **If you reuse a CC BY or CC BY-SA picture, credit it as its row in the index does** (author,
  source, licence). A CC BY-SA picture you change must be shared under the same licence.
- **Changes made to the files:** where an original was larger than 2,500 pixels on its long side, the
  file here is one of Commons' own smaller renders of it; four diagrams of the first set are renders
  of public-domain SVGs, and the pages from Stratz's book are Commons' renders of its scan. Nothing
  else was altered. Each index gives every saved file's size in pixels.
- Every picture keeps the licence in its row.

The sets were gathered and indexed by Grok at the owner's request, and placed here by Claude, who
looked at every picture outside the adults-only folder before it went in, moved to `ADULTS-ONLY/` the
unclothed ones and the men in loincloths that were not already kept apart (24 of the first set, 7 of
the second), and changed their paths in the indexes to match. Nothing else in either index is changed
from its delivery but a dated note under its first paragraph.

**If a row is wrong** (a licence, an author, a source), please open an issue: the picture will be
corrected or removed.

## Using it with Specula

Clone it anywhere; Specula does not depend on it and never reads it. It is for whoever builds a
figure, a face, a gait or a creature, person or agent, to look at beside the engine's own captures.
