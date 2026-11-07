# MC18 Dark Sun Appendix II, Terrors Beyond Tyr (TSR 2433) stat blocks: QA report

Source: `Monstrous Compendium Appendix II - Dark Sun - Terrors Beyond Tyr.pdf` (130 pages). There is no EPUB. Result: 104 creature notes in `MC18/`, plus 81 images in `MC18/images/`.

Folders: Animal (Domestic), Cactus, Crodlu, Drake (Lesser), Drik, Dune Reaper, Elemental Beast, Golem (Athasian, as `golem_athasian_mc18`), Human (Athasian), Mastyrial, Paraelemental Beast, Psurlon, Ruvoka, Scorpion (Athasian), Silt Horror, Spider (Athasian), Tari, and Tohr-kreen.

## Which file was used

`MC 18 Monstrous Compendium Appendix II - Dark Sun - Terrors of the Shore.pdf` is byte-for-byte the same file as `Monstrous Compendium Appendix II - Dark Sun - Terrors Beyond Tyr.pdf`. The "Terrors Beyond Tyr" copy was used; that is the book's real title. The product code 2433 is printed on the credits page.

## How this book was read

The PDF has a usable text layer, but every stat table was read from the page images. Page numbers are PDF page numbers. These pages have no stat table: 1-8 (covers, introduction, encounter tables), 24 (Drake, general), 37 (Elemental Beast, general), 49 (Golem, general), 77 (Paraelemental Beast, general), 121-124 (Undead, general rules), 129-130. Other pages without a table continue a creature's text.

**Psionics:** Dark Sun creatures have a psionics summary. It is kept in the `psionics` field, which the `ADnD_AI` layout does not display.

## Skipped duplicates

| MC18 entry (PDF page) | Already in |
|---|---|
| Half-giant (p. 53) | Annual 2 `Giant, Half-giant (Athasian)`: same AC 7 (10) vs 6 (10), MV 15, HD 3+12, THAC0 17, damage 1d6 or by weapon +4 |

## Kept although the name is close to one already in the vault

- **Aarakocra, Athasian:** HD 2+2, deep desert. The MC2 Aarakocra is HD 1+2.
- **Elf, Dwarf, Halfling, Human, Mul (Athasian):** the Athasian races have their own stats (e.g. Athasian elves are 7' tall, and the Mul here is HD 1+4 vs. MC12's Wild Mul at 5+5).
- **Golem, Magma and Golem, Salt:** new golems. Their folder is `golem_athasian_mc18`, because MC12 already has a `golem_athasian` folder.
- **Silt Horror, Black, Magma, and Red:** MC12 has the Brown, Gray and White silt horrors. These are the other colours.
- **Slig, Athasian:** a different creature from the MC4 (Krynn) sligs.
- **Retriever, Obsidian:** a different creature from the MC14 (Fiend Folio) `Retriever`.
- **Thri-kreen, Athasian:** similar to MC3's `Thri-kreen (Mantis Warrior)` (AC 5, MV 18, HD 6+3, THAC0 13, XP 1,400), but with different attacks (5 or 2, paralysing bite), morale (Fanatic) and size (L, 11' long).
- **Tohr-kreen, J'ez, J'hol, T'keech and Tondi:** new kreen types. MC12's `Tohr-kreen (Mantis Noble)` is a separate entry.
- **Drakes (Magma, Rain, Silt, Sun):** these are Athas's "lesser" drakes. MC12's elemental drakes (Air, Earth, Fire, Water) are different.

## Things to verify

- **Undead (Dhaot, Fael, Kaisharga, Meorty, Raaig, Racked Spirit, T'liz, Thinking Zombie):** AC, HD, THAC0 and attacks are often "as in life" with a minimum. `health` and `to_hit` give the minimum, e.g. "As in life (minimum 10-80)". XP is a base plus an amount per HD.
- **Animal, Domestic, Mulworm:** HD "1 point", THAC0 and morale N/A, XP printed as "35/7".
- **Animal, Domestic, Sygra:** males have 3 attacks and are worth 65 XP; females have 2 and are worth 35.
- **Bloodgrass:** 1 hit point per tendril; THAC0 "Special".
- **Elemental Beast, Water:** it is a school of 5-10 small beasts, each with 1+1 HD. THAC0 is "Special" and XP is 300.
- **Kragling:** two sets of values are printed in each row (e.g. HD "3, 5", XP "175, 420") and are kept that way.
- **Pakubrazi:** THAC0 is 15, or 14 with a weapon.
- **Fordorran:** AC "4/0".
- **Dray:** HD, morale, XP and psionics all "Varies"; HD is given as "3d10/4d8".
- **Silt Horror, Red:** AC "6 (8)" and MV "8 (6)" are kept as printed.
- **Spider, Dark:** XP differs for the warrior, mage and queen.
- **XP values printed as text** (several values, or a value per kind) are kept as text: Dwarf, Elf, Halfling, Human, Klar, Krag, Ssurran, Tari Chieftain.

## Images

There is no EPUB, so all art was cropped from the PDF pages. The crop boxes come from where the art images are placed on each page, so some crops include a little nearby text or a border ornament.

Pages that show several creatures share one picture: the domestic animals, Crodlu, Dune Reaper, Drik, Human, Mastyrial, Psurlon, Ruvoka, Scorpion, Spider, Tari, and the two Tohr-kreen pages. The T'liz picture shows the NPC T'liz from its page, and the Athasian Wraith picture shows the wraith NPC.

**No image:** Zombie, Thinking (no art printed).
