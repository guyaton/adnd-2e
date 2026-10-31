# MC5 (Greyhawk Adventures) stat blocks: QA report

Source: MC_5_Monstrous_Compendium_Greyhawk.pdf. Result: 68 creature notes in `mc5_bestiary/`, with a folder only for pages that cover several creatures (Aspis, Beetle, Dragonfly, Gremlin, Mite, Plant, Rat, Raven, Snail, Sprite, Turtle, Wraith).

## How this book was read

The PDF is an OCR scan whose text layer drops the shaded rows of every stat block, so the stat tables were read from the page images, not from the OCR. Page numbers are PDF page numbers (the book has no printed numbers). Pages 15-16 (general dragon rules), 61-64 (random-encounter tables, including the Cold Region Encounters table) and 65-68 (full-page art) hold no creatures and were skipped.

## Things to verify

- Giant Iguana: the printed table has no TREASURE row, so `treasure` is blank.
- Snail (Flail, Sea): the Morale row was faint on the scan; both read Elite (13-14).
- Tyrg: the last XP line (8 HD: 975) was partly cut off on the scan.
- Complex values (several HD or ages in one cell, like Aspis Larva or Tyrg) keep the printed text, and the numbers in them were converted by hand: AC 20 - AC, to_hit 20 - THAC0.
- Horgar head AC, Dragonnel AC and the Vampire Cactus parts were converted by hand as well.

## Health field

Same rule as MC1: every die is a d8, so N HD = N to 8N (printed hit points are used as printed). Left blank: Brownie, Quickling, Soul Beckoner. A few were entered by hand from the printed HD (Horgar, Spriggan, Tentamort, Vampire Cactus, Zygom).

## Summaries

Added (paraphrased from the book text) to the 29 creatures whose Special Attacks or Special Defenses say "See below" or "Special", plus the Mite and the Mist Wolf: Aspis Cow, Aspis Drone, Aspis Larva, Atomie, Brownie, Buckawn, Brownie, Quickling, Cloud Dragon, Crypt Thing, Crystalmist, Flail Snail, Greyhawk Dragon, Grig, Kech, Mist Dragon, Mist Wolf, Mite, Necrophidius, Needleman, Scarecrow, Sea Snail, Shadow Dragon, Skulk, Snyad (Pestie), Son of Kyuss, Spriggan, Taer, Tentamort, Valley Elf, Vampiric Mist.

The four dragons list their breath, powers and spells by age category in the book, so their summaries cover abilities, not the age table values.
