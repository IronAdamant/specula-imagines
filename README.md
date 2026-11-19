# Specula imagines: reference pictures

> **Adults only (18+) for one folder.** [`ADULTS-ONLY/`](ADULTS-ONLY/README.md) holds 86 unclothed
> anatomical plates, figure studies and motion studies from the 16th to the 19th century (Dürer,
> Albinus, Richer, Stratz, Vanderpoel, Muybridge and a sculpted muscle figure), two of them
> dissections of the trunk from an atlas of 1909. They show the whole
> body, genitals included, because that is how anatomy and gait were recorded. Nothing here is sexual,
> and no picture of an unclothed child is in this repository at all. Everything outside that folder is skeletons, parts of the body,
> heads and faces, clothed or draped figures, animals, and drawings for 2D work.

**This is an agent reference repository.** I (IronAdamant) keep it for the
[Specula](https://github.com/IronAdamant/Specula) game engine: it is what the AI agents that work
through that engine look at when they build a character's skeleton, a figure, a creature or a piece
of animation, the way an artist keeps anatomy plates beside the drawing board. Its only purpose is
reference for building characters and motion in games, in whatever style a game has.

576 pictures that Specula's figures, creatures and effects are held against while they are built:
anatomical plates, skeletons, muscle figures, studies of people and animals in motion, faces and their
expressions, skeletons of animals by body plan, model sheets for 2D, and, for the engine's effects and
physics, fire, lightning, explosions, light and dark, things breaking, and weapons with the plates of
the old fencing masters. Every one is in the public domain or under a Creative Commons licence that
allows this, and every one has its source, its author and its licence in an index:
[INDEX.md](INDEX.md) for the first 110, [INDEX-round-2.md](INDEX-round-2.md) for the next 159,
[INDEX-round-3.md](INDEX-round-3.md) for the 88 after them, [INDEX-round-4.md](INDEX-round-4.md)
for the 10 after those and [INDEX-round-5.md](INDEX-round-5.md) for the last 217 (the trunk, the
shoulder and arm, hands and feet, close up).

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
was gathered from are Specula's `docs/research/REFERENCE_IMAGES_BRIEF.md`,
`docs/research/REFERENCE_ROUND2_BRIEF.md` and those after it (the fifth set answers
`REFERENCE_ROUND5_BRIEF.md`), and the figure being built against it is described in
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
| `4-motion/` | 45 | A walking stride as a diagram with its phases and as five photographs; Muybridge: clothed or draped people on stairs, lifting and sitting; horses, oxen, goats, deer, dogs, cats, a lion, an elephant, camels, a kangaroo, baboons; pigeons, an eagle, a vulture, ostriches |
| `5-creatures/` | 61 | A skeleton and other views for each body plan: dog, lion, horse, cow, goat, deer, bear, elephant, ostrich and other birds, bat, pterosaur, lizard, crocodile, snake, fish, insects, spiders |
| `6-2d/` | 16 | Walk-cycle key poses, turnaround and model sheets, jointed and cut-out figures |
| `7-fire-smoke/` | 17 | Candle and burner flames, flame colours by fuel, camp fires, wildfire smoke from the air and from orbit, a fireball, the first frames of a nuclear test |
| `8-lightning/` | 11 | Strikes by night, a stepped leader in slow motion, trees and sand a strike has marked |
| `9-explosion/` | 7 | Test detonations on land and at sea, shock waves made visible, a crater, glass breaking |
| `10-light-dark/` | 10 | Twilight, moonlight, a sodium lamp, the night sky, light through mist, the colour of light by temperature |
| `11-shape-bounce/` | 1 | A bouncing ball caught by a strobe |
| `12-destruction/` | 17 | Buildings brought down, earthquake damage, rubble, cracked and spalled concrete, broken rock and glass, a split log |
| `13-weapons-fencing/` | 25 | Museum swords, a sabre, rapiers, a dagger, an axe, a mace, a halberd; plates of guards, cuts and grips from the fencing treatises of the 15th to 17th centuries |
| `14-clothing-patterns/` | 2 | Flat patterns: a man's shirt of 1898 with its measurements, a bodice from a museum's study collection |
| `15-trunk/` | 38 | The trunk close up: frozen cross-sections at the shoulders and the hips (Braune), the rib cage and sternum, the muscles of the back, neck, belly and buttocks layer by layer (Richer, Sobotta) |
| `16-shoulder-arm/` | 56 | The shoulder girdle as bone from every side and from above, its joints and ligaments, the muscles of the shoulder, upper arm and forearm in layers, where each muscle attaches to each bone (Spalteholz), the arm as a living surface with its key (Richer) |
| `17-hands/` | 40 | Hands photographed from the back, the palm and the side, old and young, in grips (a pen, a knife, a tool, eggs, crochet); the palm's creases; bones, X-rays, tendons, muscles and their attachments |
| `18-feet/` | 50 | A foot's bones photographed from three sides, prints of one foot sitting, walking and standing, flat and high arches, X-rays of feet in shoes (Munson, 1912); the ankle, the sole and the lower leg in layers; where the muscles attach |
| `ADULTS-ONLY/1-whole-body/` | 28 | Whole unclothed figures of men and women, living and as muscle figures, front, side and back; two builds side by side; a proportion canon |
| `ADULTS-ONLY/2-weak-areas/` | 3 | The hips from the front and the side; the shoulders on a whole figure |
| `ADULTS-ONLY/4-motion/` | 22 | Muybridge: men walking, running, jumping, climbing, carrying and rising, unclothed or in a loincloth, and one woman (his model 1, "a widow, aged thirty-five") walking and carrying; plates with matched side, front and back rows of one walk |
| `ADULTS-ONLY/15-trunk/` | 13 | Richer's model: the trunk as a living surface front, side and back, each with its outline key; the loins, the fold of the buttock, the hips standing on one leg; two dissections of the trunk that show the groin (Sobotta) |
| `ADULTS-ONLY/16-shoulder-arm/` | 12 | Richer's model: the trunk as the shoulder is raised, lowered, drawn forward and back, and as the arm is held level and straight up, from the front, the side and the back, each with its key; the elbow bending |
| `ADULTS-ONLY/18-feet/` | 8 | Richer's model: the leg and foot as a living surface from the front, the back and both sides, each with its key |

**Still missing**, by the indexes' own account: matched front, side and back sets of slender, muscular
and older bodies; a whole figure at three-quarter; a large open sheet of a walk cycle's key poses;
cross-sections of the trunk at the nipple, the waist and the navel; a woman's trunk as a surface; the
arm raised in steps; a hand from the little-finger side and end on; a foot on tiptoe, pointed and
pulled up.
Each index says how well each kind is covered and lists what was found and not taken, with the reason.
**No unclothed figure of a child is here, drawn or photographed.** Plates of unclothed children were
left out when the sets were gathered, and a chart of proportions by age (doll-like figures with no
clothes drawn on them) and one drawing whose subjects could not be shown to be adults were taken out
when the second set was placed, and are not kept here in any form. The only children pictured are
clothed: the faces of infants and children in Darwin's plates of expressions (1872).
**Nor is any unclothed photograph here of someone who cannot be shown to have been an adult.**
Muybridge's own catalogue of 1887 numbers his models and says who they were: his athletes were men of
eighteen to twenty-four, three boys of thirteen to fifteen posed for plates that were never here, and
a group of his women were "of ages varying from seventeen to twenty-four". Nine plates of women from
that group, or of women whose age he does not give, were taken out on 2026-11-19 when the catalogue
was read against every plate ([INDEX-round-2.md](INDEX-round-2.md) has the list).

## Sources and licences

All 576 files come from Wikimedia Commons, or from the Metropolitan Museum of Art's Open Access
collection for some of the weapons. **Every one is in the public domain, CC0, CC BY or CC BY-SA**, and
none is non-commercial or no-derivatives. Of the first two sets (269 files), 200 are in the public
domain, 31 are CC0, 30 are CC BY and 8 are CC BY-SA; the third index counts its own set, in which the
share-alike licences are commoner (photographs of fire, storms and ruins), and the fifth its own
(180 of its 217 in the public domain).

Each index has a row for every picture: the file, what it shows, the view, the subject, the Commons
page it came from with its author or collection and year, the licence with the link that states it,
and the date it was checked (2026-11-17 to 2026-11-19). Licence, author and size were read from the Commons record
for each file, not guessed.

- **If you reuse a CC BY or CC BY-SA picture, credit it as its row in the index does** (author,
  source, licence). A CC BY-SA picture you change must be shared under the same licence.
- **Changes made to the files:** where an original was larger than 2,500 pixels on its long side, the
  file here is one of Commons' own smaller renders of it; four diagrams of the first set are renders
  of public-domain SVGs, and the pages from Stratz's book are Commons' renders of its scan. In the
  fifth set the renders go up to 3,840 pixels, and two line drawings saved with a transparent ground
  are flattened onto white. Nothing else was altered. Each index gives every saved file's size in
  pixels.
- Every picture keeps the licence in its row.

The sets were gathered and indexed by Grok at the owner's request, and placed here by Claude, who
looked at every picture outside the adults-only folder before it went in, moved to `ADULTS-ONLY/` the
unclothed ones and the men in loincloths that were not already kept apart (24 of the first set, 7 of
the second), and changed their paths in the indexes to match. Of the third set, three photographs that
show mostly people at a disaster or at work were not placed, and its folders are numbered on from the
earlier ones. Of the fifth set, all 217 were looked at before any went in (the unclothed ones too: all are
Richer's adult model), and two dissections that show the groin were moved to `ADULTS-ONLY/`. Each
index has a dated note under its first paragraph saying what was changed from its delivery.

**If a row is wrong** (a licence, an author, a source), please open an issue: the picture will be
corrected or removed.

## Using it with Specula

Clone it anywhere; Specula does not depend on it and never reads it. It is for whoever builds a
figure, a face, a gait or a creature, person or agent, to look at beside the engine's own captures.
