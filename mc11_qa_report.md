# MC11 Forgotten Realms Appendix II (TSR 2125) stat blocks: QA report

Source: `MC 11 Monstrous Compendium Forgotten Realms Appendix II.pdf` (70 pages). There is no EPUB for this book, so all art was cropped from the PDF. Result: 42 creature notes in `MC11/`, plus 29 images in `MC11/images/`. Twenty entries were skipped as duplicates (see below).

Folders: Alguduir, Cat, Harrier, Plant (Carnivorous), and Rohch.

## How this book was read

The PDF has a text layer, but it drops values, so every stat table was read from the page images. Page numbers are PDF page numbers. Pages 1-3 are covers and the contents; 66-70 are covers and blank. These pages continue a creature's text: 7, 12, 17, 19, 27, 33, 39, 55, 59 and 63.

## Skipped duplicates

MC11 reprints many creatures that were later collected in other books already in the vault:

| MC11 entry (PDF page) | Already in |
|---|---|
| Alaghi (p. 4) | Annual 3 |
| Avian: Flightless, Boobrie, Eblis (p. 6) | Monstrous Manual `Bird` folder |
| Bat, Deep: Azmyth, Night Hunter, Sinister (p. 8) | Monstrous Manual `Bat` folder (only the Deep Bat Werebat column is new) |
| Cat: Domestic, Wild, Elven (p. 11) | Monstrous Manual `Cat, Small` folder |
| Chitine (p. 13) | Annual 1 |
| Cildabrin (p. 14) | Annual 3 |
| Dragon, Deep (p. 16) | Monstrous Manual |
| Elf, Aquatic (p. 18) | Monstrous Manual |
| Feyr, Feyr, Great (p. 21) | Monstrous Manual |
| Firetail, Lesser and Tshala (p. 22) | Annual 3 |
| Giant, Mountain (p. 25) | Monstrous Manual |
| Gloomwing Moth (p. 26) | Monstrous Manual `Gloomwing` |
| Hamadryad (p. 30) | Annual 3 `Dryad, Hamadryad` |
| Inquisitor (p. 37) | Annual 4 |
| Loxo (p. 40) | Annual 1 |
| Naga, Dark (p. 44) | Monstrous Manual |
| Peryton (p. 46) | Monstrous Manual |
| Plant, Carnivorous: Retch Plant, Snapper-Saw, Thornslinger (p. 48) | Monstrous Manual `Plant, Dangerous` folder |
| Saurial (p. 54: four types) | Annual 3 |
| Spider, Monkey (p. 61) | Monstrous Manual `Mammal, Monkey Spider` |
| Tempest (p. 62) | Monstrous Manual `Elemental, Composite, Tempest` |

Kept as separate creatures because their stats differ:
- **Ammonite, Golden (MC11):** AC 6/8 and 8,000 XP here, vs. AC 2/8 and 6,000 XP in Annual Four.
- **Tlincalli:** 7+7 to 11+11 HD here, vs. the Monstrous Manual's 8-12 HD Manscorpion (Tlincallis).
- **Gloomwing, Flying Serpent:** a different creature from the gloomwing moth on the same page.

## Things to verify

- **Golem, Lightning:** XP printed as "2,004". Kept as printed.
- **Phantom:** every combat stat is "Nil" (it is a harmless image).
- **Silver Dog:** THAC0, attacks and damage are "NA"; XP is "1,000 or -1,000" (depending on how it is treated).
- **Bat, Deep, Werebat:** most stats vary by the original creature.
- **Frost:** morale printed as a bare "12".
- **Rohch:** morale is printed as a word only (Average, Elite, Champion).

## Values converted by hand

- **AC with two values:** Fachan (head AC 2), Frost (9, or 5 flying), Ammonite (MC11) (shell/arms), Lhiannan Shee (three light levels), Sha'az (with shield), Whip-Weed (6/4).
- **THAC0 by HD:** Cantobele, Dimensional Warper, Wither-Weed, Black Willow, Tlincalli.
- **Health:** Cantobele, Dimensional Warper, Frost and Haun (1-4 hp), Golem, Lightning (66 hp), Simpathetic (4 hp), Ring-worm (1 hp), Wither-Weed, Black Willow, Tlincalli.

## Images

All art was cropped from the PDF. Some crops include a little page text.

**No image:** Ammonite, Golden (MC11) (no art printed), Bat, Deep, Werebat, Cat (Luck Eater, Change Cat), the three Carnivorous Plants on p. 49, and the four Rohch. These pages have tables only, or their art shows a skipped creature.

## Fix made to the Monstrous Manual folder

While checking duplicates for this book, a recheck of the Monstrous Manual index found that its **Gibberling** had been missed (the name check had matched it to Annual Four's Brood Gibberling). It has now been added to `Monstrous Manual/`.
