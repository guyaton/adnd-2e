# MC4 Dragonlance Appendix (TSR 2105) stat blocks: QA report

Source: `MC 4 Monstrous Compendium Dragonlance.pdf` (100 pages). There is no EPUB for this book yet. The PDF has its illustrations embedded, so the art was extracted directly rather than cropped. Result: 89 creature notes in `MC4/`, plus 57 images in `MC4/images/`. Four duplicates were skipped (see below).

Pages with several creatures are in folders: Avian, Beast (Undead), Centaur (of Krynn), Dragon (Astral), Hatori, Insect Swarm, Lizard Man (of Krynn), Man (of Krynn), Ogre (of Krynn), Phaethon, Shadowperson, Slig, Spider (of Krynn), and Tayling.

## How this book was read

The PDF has a text layer, but it drops dashes (so "1-10" reads as "110"), so every stat table was read from the page images. Page numbers are PDF page numbers. Pages 1-3 are the cover, introduction and index; 90-93 are encounter tables; 94-95 are a statistics summary table; 96-100 are blank or covers. These pages continue a creature's text: 12, 18, 19, 27, 45, 55, 59, 61-63, 65, 67, 69, 71, 73, 77, 81 and 83.

## Missing entries: Krynn centaurs and Sligs

The book's index lists a "Centaur (of Krynn)" entry (Abanasinian, Crystalmir, Endscape and Wendle centaurs) and a "Slig" entry (Slig, Warrior, Champion and Ghaggler). **Neither entry is in this PDF.** Page 9 holds the standard Sylvan Centaur instead, which is the same as MC1's.

These eight creatures do appear in the summary table on pp. 94-95, so they were added from it. Their notes only have what that table prints: number appearing, AC, movement, HD, attacks, damage, THAC0, alignment, and whether they have special attacks or defenses. Climate, frequency, size, morale and XP are missing. Their `original_src` says "statistics summary table only". If you find a copy with the full pages, these can be completed.

## Skipped duplicates

| MC4 entry (PDF page) | Already in |
|---|---|
| Cave Fisher (p. 8) | MC1 `Cave Fisher` |
| Centaur, Sylvan (p. 9) | MC1 `Centaur, Sylvan` |
| Stag, Wild (p. 79) | Annual 2 `Stag, Wild` |
| Stag, Giant (p. 79) | Annual 2 `Stag, Giant` |

The White Stag on p. 79 is new and was kept.

Krynn versions of common creatures were kept because their stats differ: Ice Bear (vs. Polar Bear), Giant Anemone (vs. Annual 4's Giant Sea Anemone), Blood Sea Minotaur (vs. Minotaur), Ogre (of Krynn) (vs. Ogre), Lizard Men of Krynn (vs. Lizard Man), Knight Haunt (vs. Haunt), the Krynn dwarves and elves (vs. MC2's dwarves and Elf), and Tinker Gnome (vs. Gnome).

## Name changes

- Em-dashes in titles are written as hyphens, e.g. `Elf, High-Qualinesti`, `Elf, Sea-Dargonesti`.
- `Dragon, Sea (Krynn)` and `Elf, Half (Krynn)` have "(Krynn)" added so they are clearly the Dragonlance versions.
- `Minotaur (of Krynn), Blood Sea Minotaur` uses the column name from the table.
- **Dragon, Othlorx** (p. 23) is a description of renegade chromatic and metallic dragons with no stat block, so it has no note.

## Things to verify

- **Dragon, Kodragon:** XP printed as "2,00". Kept as printed. The No. of Attacks cell is blank, so it is stored as "Not printed" (damage lists three attacks).
- **Man (of Krynn):** the damage and XP rows are blank lines in the table. Damage is "By weapon" (from the summary table) and XP is "Not printed (varies by level)". The Rebels' No. of Attacks is blank.
- **Spider (of Krynn):** the table has no No. Appearing row. Stored as "Not printed".
- **Tayling, Tayland:** the Organization cell is blank.
- **Wichtlin:** the Frequency cell is blank.
- **Shadowperson, Revered Ancient One:** every combat stat is "Nil".
- **Disir, Fire Minion, Gurik Cha'ahl, Horax, Knight Haunt, Skrit, Yaggol, Yeti-kin:** morale is printed as a bare number. Kept as printed.
- **Dwarves, elves, kender, gnomes, Irda, Blood Sea Minotaur:** XP is "Varies" because these are character races with class tables. The class-limit tables are not in the notes.
- **Amphi Dragon, Sea Dragon (Krynn), Tylor:** the age tables are not included. Only the main stat block is.

## Values converted by hand

- **AC with an unarmored value:** the dwarves, elves, kender, Tinker Gnome, Irda, Blood Sea Minotaur, Ice Folk, Knights of Solamnia, Phaethons and Tayling list armored AC with base AC in brackets, e.g. `4 (10)` becomes `16 (10)`.
- **Other AC:** Blood Sea Imp (4 or 1 in mist form), Knight Haunt (2 or better).
- **Health:** Hatori (1-5 and 6-20 HD), Death Knight (9 d10 Hit Dice: 9-90), Shimmerweed (1 hp), Skeleton Warrior (9+2 to 9+12), Plainsmen and Rebels (1-6 hp), Insect Swarm (1 hp per 20 insects).

## Images

All 57 images are the book's own illustrations, extracted at the resolution stored in the PDF (about 256 pixels square). They are smaller than images from other books.

**No image** (no art printed for them): the four Avians, Gully and Theiwar dwarves, the two sea elves, the four Men of Krynn, Ogre and Orughi, the White Stag, and the eight summary-table-only centaurs and Sligs.
