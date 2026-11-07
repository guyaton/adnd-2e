# MC17 Mystara Appendix (TSR 2501) stat blocks: QA report

Source: `MC 17 Monstrous Compendium - Mystara Appendix.pdf` (130 pages), with illustrations from `ebook/MC 17 Monstrous Compendium - Mystara Appendix.epub`. Result: 175 creature notes in `MC17/`, plus 114 images in `MC17/images/`.

Folders: Bird, Dragonfly, Drake (Mystaran), Elemental of Chaos, Elemental of Law, Familiar, Frost Salamander, Fundamental, Gargantua, Golem, Gray Philosopher, Guardian Warrior, Herex, Hivebrood, Hutaakan, Imp, Jellyfish (Giant), Lizard, Lizard-kin, Magen, Nightshade (Mystara), Plant (Dangerous), Plasm, Shapeshifter, Spider-kin, Spirit, Statue (Living), Tortle, Worm, Wyrd, and Zombie (Lightning).

## Which file was used

There is also a "bad cover" copy of this PDF. The normal file was used.

## How this book was read

The EPUB's OCR is poor for this book, and the PDF text layer drops or garbles many values. Every stat table was read from the page images, and the text layer was only used to confirm long XP and THAC0 lists. Page numbers are PDF page numbers; EPUB page N is PDF page N+1.

These pages have no stat table: 16, 34, 36, 43, 61, 67, 72, 74, 79, 85, 90, 98, 105, 107, 109 and 120 continue a creature's text, and 28 is the general introduction to the gem dragons.

## Skipped duplicates

| MC17 entry (PDF page) | Already in |
|---|---|
| Brain Collector (p. 18) | Annual 4 `Neh-thalggu` (same AC, MV, HD, THAC0, damage and XP) |
| Pegataur (p. 87) | Annual 3 |
| Spider-kin, Aranea (p. 104) | Annual 3 `Aranea` |

## Kept although the name is already used

- **Lycanthrope, Werejaguar (Mystara):** this has different stats from the Annual 1 werejaguar (MV 18 vs. 15, bite 1d8, XP 2,000 vs. 975), so it was kept and renamed.
- **Dragon, Jade:** this is not the same creature as Annual 1's oriental `Dragon, Neutral, Jade`. The Mystaran one is a gem dragon (AC -1, HD 13).
- **Nightshade (Nightcrawler, Nightwalker, Nightwing):** these are undead from the Negative Energy Plane. They have nothing to do with Annual 1's plant creature `Nightshade`.
- **Worm, Leviathan (Desert and Marine):** these are not the same creature as the MC2 whale `Leviathan`.
- **Golem, Rock:** the file was renamed `golem_rock_mystara.md` because MC12 already has a `golem_rock.md` (the Athasian rock golem). The two creatures have different printed names.

## Things to verify

- **Drakes (Mandrake, Wooddrake, Colddrake, Elemental):** movement is read as "12, Fl 3 (D)". The text says their wings support only slow flight, so the low flying speed fits, but the print is small.
- **Blackball:** it has no Hit Dice, THAC0 or attacks ("None (see below)"), so `health` reads "See below" and `to_hit` reads "Nil".
- **Diabolus:** AC, HD, THAC0, morale and XP all "vary" or are "see below" (the creature is built like a character).
- **Horde:** THAC0, damage and XP depend on Hit Dice; a table in the text gives the values.
- **Hivebrood Broodling:** HD is "as host +1d4 hp or 2+1, whichever is greater".
- **Sollux:** THAC0 is printed going down by 1 per Hit Die (11 at 10 HD to 7 at 14 HD). Kept as printed.
- **Thunderhead:** HD, THAC0 and XP double in thunderstorms (16 HD, THAC0 5, XP 10,000).
- **Spirit, Druj:** damage is listed separately for the eye, hand and skull forms.
- **Hutaakan, Imps, Lupin, Sis'thik, Tortle:** AC has a second value in brackets (without armor or with the shell closed).
- **Statue, Living, Rock/Ooze:** this is one column covering two kinds; XP is 420 (rock) or 650 (ooze).
- **Huptzeen:** size is printed as "T-M (2"-5')".

## Values converted by hand

- **THAC0 and XP by Hit Dice:** Elemental of Law Hydrax, Herex Larva, Hsiao, Huptzeen, Mek, Sollux, Spider-kin Planar Spider.
- **Health:** Worm, Great Annelid (25-50 HD = 25-400 hp), Thunderhead (both forms), Hivebrood, Plant (Dangerous) Grab Grass (per 5' square).

## Images

Most art comes from the EPUB. Where the EPUB has no picture, the art was cropped from the PDF page. That covers the magpie, piranha bird, Blackball, Darkhood, crystalline dragon, dragonfly, Erdeen and Eolian, Helion and Hydrax, iron gargoyle and mud golems, Herex, Horde, giant jellyfish, Kopru, lizard-kin, Magen, Mystaran nightshade, Scamille, Sollux, Spectral Death, Spectral Hound, Tortle, White Fang and Red Worm. Some PDF crops include a little of the page's text.

Creatures that appear together in one picture share it. Examples are the Eolian and Erdeen, Pyrophor and Undine, Anemo and Kryst, the four Fundamentals in pairs, Amber and Skeletal golems, Rock and Silver golems, Wood and Bog imps, and the drakes.

**No image:** Lesser and Greater Sprackle, Gargantua Carrion Crawler and Troll, Snapper (Tortle page), and the Great Annelid, Caecilia, Fyrsnaca, both Leviathans and the Slime Worm.
