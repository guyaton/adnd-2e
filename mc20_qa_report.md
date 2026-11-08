# MC20 Ravenloft Appendix III, Creatures of Darkness (TSR 2153) stat blocks: QA report

Source: `MC 20 Monstrous Compendium III - Creatures of Darkness.pdf` (126 pages). The EPUB `ebook/MC 20 Monstrous Compendium III - Creatures of Darkness.epub` was used for its text. Result: 117 creature notes in `MC20/`, plus 106 images in `MC20/images/`. The product code 2153 is printed on the cover.

Folders: Animator, Beetle (Scarab), Cat, Cloaker (Ravenloft), Familiar (Ravenloft), Figurine, Ghost (Animal), Golem (Ravenloft), Hag (Spectral), Hound (Ravenloft), Leech (Ravenloft), Lich, Living Tatoo, Lycanthrope (Loup-garou), Plant (Ravenloft), Sea Spawn, Skeleton (Ravenloft), Vampire (Ravenloft), Virus, Will O' Wisp (Ravenloft), and Zombie (Ravenloft).

## How this book was read

The PDF is a scan with no text layer. The EPUB's OCR jumbles the stat tables, so every table was read from the page images. Page numbers are PDF page numbers. These pages have no stat table: 1-7 (covers, credits, introduction, cross-reference list), 9 (Animator, general), 37 (Figurine, general), 111 (Virus, general), and 126 (back cover). Other pages without a table continue a creature's text.

**Psionics:** Lich, Defiler and Spirit, Psionic have a psionics summary. It's kept in the `psionics` field, which the `ADnD_AI` layout doesn't display.

## Skipped duplicates

| MC20 entry (PDF page) | Already in |
|---|---|
| Carrionette (p. 20) | Annual 1 (same AC, MV, HD, THAC0 and XP) |
| Death's Head Tree (p. 27) | Annual 1 `Tree, Death's Head` (same AC, HD 10 + 6 hp/head, THAC0 11; Annual 1 gives XP 5,000, MC20 gives 1,400) |
| Lich, Psionic (p. 74) | Annual 1 (same AC, MV, HD 9+18, THAC0, damage and XP) |
| Zombie, Wolf (p. 125) | Annual 1 `Wolf, Zombie` (same AC, MV, HD, THAC0, damage; XP 120 here vs. 65) |

## Kept although the name is close to one already in the vault

- **Doppleganger, Ravenloft:** HD 5 and organised in clans; the MC2 doppleganger is HD 4.
- **Golem, Ravenloft, Flesh:** AC 6, MV 12 and Average intelligence; the MC1 flesh golem is AC 9, MV 8 and mindless.
- **Lycanthrope, Werejaguar (Ravenloft):** AC 5, MV 18, HD 5, lawful neutral; differs from both Annual 1's and MC17's werejaguars.
- **Vampire, Oriental:** HD 9+3, MV 12, Fl 6 (C); not the same as MC15's NPC `Vampire, Eastern (Mayonaka)`.
- **Hag, Spectral (Annis, Green, Sea):** undead versions of the Monstrous Manual hags.
- **Skeleton, Strahd and Zombie, Strahd:** not the same as MC10's `Strahd's Skeletal Steeds`.

## Things to verify

- **Animators, Pseudo-familiar, Hearth Fiend, Obedient, Paka:** AC, HD, THAC0 and XP are "Varies" in the book (they depend on the possessed object, the host, or the character class).
- **Viruses:** AC, HD and number appearing are "N/A"; they are diseases rather than creatures.
- **Geist:** has no HD, THAC0 or attacks, and is worth 0 XP.
- **Odem and Fleas of Madness:** AC and HD are "N/A".
- **Ivy, Crawling:** HD "7 or 8"; morale is printed as just "11".
- **Shattered Brethren:** HD 3, but the text says they always have at least 7 hp per Hit Die, so health is 21-24.
- **Zombie Fog:** HD 6-10 and THAC0 "Varies"; XP by HD as printed (8 HD is printed as 2,000, the same as 7 HD).
- **Lich, Defiler:** HD "11+".
- **Cat, Midnight and Cat, Skeletal:** morale printed as "Very steady" and "Fearless" with no number.
- **Werejackal, Werejaguar, Wereleopard, Wereray:** XP is given separately for true and cursed lycanthropes.
- **Living Tatoo:** "Tatoo" is the book's spelling.

## Images

The art was cropped from the PDF scans (the EPUB's pictures are mostly whole-page scans that include the stat table). Several creatures on the same page share one picture: the three scarab beetles, the Crystal and Diamond figurines, the three spectral hags, both Loup-garou, the Drow and Drider liches, the insectoid skeletons, each pair of viruses, and the Zombie Fog and its cadavers.

**No image:** the six animal ghosts and the five living tatoos (their pages have no art).
