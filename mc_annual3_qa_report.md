# MC Annual Volume Three (TSR 2166) stat blocks: QA report

Source: `Monstrous Compendium - Annual Volume 3.pdf` (130 pages), with illustrations from `ebook/Monstrous Compendium Annual Volume 3.epub`. Result: 128 creature notes in `MC Annual 3/`, plus 99 images in `MC Annual 3/images/`. Four duplicates were skipped (see below).

Pages with several creatures are in folders: Beetle, Dream Spawn (Lesser-Morph), Firetail, Formian, Gargoyle, Giant (Cerilian), Human (Cerilian), Life-Shaped Guardians, Life-Shaped Transport, Orc (Neo-Orog), Owlbear, Saurial, Thessalmonster, Time Dimensional, Web (Living).

## How this book was read

The PDF and EPUB are both OCR scans. The text layer is about 27% accurate and drops the shaded rows of most stat tables, so every stat table was read from the page images, not from the OCR. Page numbers are PDF page numbers. Pages 1-6 (front matter), 121-128 (cumulative index) and 129-130 (back cover) hold no creatures. Pages 31, 40, 42, 51, 60, 63, 66, 68, 73, 75, 92, 93, 103, 105 and 111 continue a creature's text and have no stat table of their own.

## Skipped duplicates

These creatures are already converted from MC5 (Greyhawk) with the same stats, so the Annual Three entries were left out:

| Annual Three (PDF page) | Already in |
|---|---|
| Beetle, Deathwatch (p. 13) | MC5 `Death Watch Beetle` |
| Beetle, Slicer (p. 13) | MC5 `Slicer Beetle` |
| Kyuss, Son of (p. 70) | MC5 `Son of Kyuss` |
| Needleman (p. 83) | MC5 `Needleman` |

The only differences are wording: dice written as `3d4` instead of `3-12`, and Death Watch Beetle's special attack called "Death rattle" instead of "Death vibration". The removed notes are in the vault's `.trash/MC Annual 3 duplicates/` folder. The Beetle folder now holds only Beetle, Stink.

These look similar to existing creatures but are different variants with different stats, so they were kept: Arctic and Winged Owlbear (vs. Owlbear), Black Unicorn (vs. Unicorn), Cerilian Goblin (vs. Goblin), Ixzan (vs. Ixitxachitl), Neo-Orog (vs. Orog), Hamadryad (vs. Dryad), Undead Dragon Slayer (vs. Human, Dragon Slayer), and Archer, Spouter, Stone Lion and Grandfather Plaque Gargoyles (vs. Gargoyle).

## Name changes

- Em-dashes in titles are written as hyphens, e.g. `Spirit, Forest-Uthraki`, `Tanar'ri, Greater-Goristro`.
- Column names were added to group members, e.g. `Formian, Worker`, `Giant, Cerilian Ice`, `Life-Shaped Guardian, Climbdog`.

## Things to verify

- **Thessalmonster:** the printed table has no SIZE row, so `size` is blank for all four.
- **Human, Cerilian:** the table only prints Frequency, Treasure, Alignment, No. Appearing, AC, HD, THAC0, Morale and XP, so the other fields are missing.
- **Hound of Ill-Omen:** the printed table has no TREASURE row.
- **Mastiff, Shadow:** the printed table has no TREASURE row.
- **Cildabrin:** morale is printed as "14 (Elite)", the reverse of the usual order. Kept as printed.
- **Firenewt:** the Overlord XP (420) is lower than the Priest XP (650). Kept as printed.
- **Web, Memory:** XP printed as "3000" without a comma.
- **Formian, Queen:** THAC0, attacks and damage are all "Nil", so `to_hit` is blank. The same applies to Gargoyle, Grandfather Plaque, Life-Shaped Shieldbug and Watcher, and Life-Shaped Gon-evauth (attacks).
- **Faerie, Petty-Bramble and Petty-Gorse:** HD is printed in hit points (2 hp and 1 hp).

## Values converted by hand

The normal rules are: AC = 20 - printed AC; to_hit = 20 - THAC0; health uses d8s (N HD = N to 8N; N+X = N+X to 8N+X). These creatures needed manual conversion:

- **AC with several values:** Dragon, Cerilian ("0 or better"), Dread Warrior (2 to 4), Dwarf, Arctic (8 (10)), Elf, Rockseer, Faerie, Petty-Bramble/Gorse, Goblin, Cerilian, Head, Arcane, Human, Cerilian, Mist, Scarlet Dancer, Orc, Neo-Orog, Orc, Ondonti, Pegataur, Sharn, Thessalmera (5/2/0), Undead Dragon Slayer.
- **THAC0 by HD:** Bladeling, Elf, Rockseer, Goblin, Cerilian, Human, Cerilian Anurien, Ixitxachitl, Ixzan, Mist, Scarlet Dancer, Pegataur, Temporal Glider, Time Dimensional, Common, Undead Dragon Slayer, Web, Living.
- **Health:** Banelich (17-136, at its 17 HD minimum), Bladeling (2 to 11 HD), Chronovoid (12+1 total), Eel, Giant Moray (5 to 5+12 HD), Elf, Rockseer, Giant, Cerilian (HD printed with extra hp: 16+6 hp and 15+7 hp), Goblin, Cerilian, Golem, Magic and Golem, Shaboath (printed hp), Human, Cerilian, Ixitxachitl, Ixzan, Jabberwock and Render (printed hp), Life-Shaped Guardians, Mist, Scarlet Dancer (1 HD per 10 dancers), Orc, Ondonti, Pegataur, Reggelid, Tanar'ri, Greater-Goristro (20+120 = 140-280), Temporal Glider, Time Dimensional, Undead Dragon Slayer (d10 Hit Dice, as printed), Web, Living.
- **Size:** Goblin, Cerilian, Ixitxachitl, Ixzan, Lycanthrope, Werecrocodile and Werespider, and Weredragon have two sizes, so `size` and `size_detail` hold both.

## Psionics

Alhoon, Belgoi, Braxat, Bvanen and Tembo have a printed psionics summary. It is stored in a new `psionics` field. The `ADnD_AI` layout will not show it unless you add that field to the layout. The rest of the note works either way.

## Images

The EPUB has art for most creature pages. Art missing from the EPUB was cropped from the PDF scan: Gargoyle (Archer, Spouter), Head, Arcane, Human, Cerilian, Ibrandlin, Life-Shaped Guardians (Climbdog, Darkstrike, Protector, Shieldbug, Watcher), Life-Shaped Ber-ethern, Phaerimm, Saurial and Weredragon. Some crops show a little nearby text.

Art taken from a continuation page: Tome Guardian (p. 40), Gon-evauth (p. 73), Saurial Hornhead (p. 93), Goristro (p. 103), Armanite (p. 105) and Thessalmonster (p. 111). The Gon-evauth and Hornhead images were matched from their descriptions, not captions.

**No image** (no art printed in the book): Beetle (all three), Dragon, Ghost Dragon, Formian (all four), Gargoyle Stone Lion and Grandfather Plaque, Imp, Chaos, Life-Shaped Dhev-sahr and Yihn-eflan, and Time Dimensional (all three).

Group members share the page image unless they have their own.
