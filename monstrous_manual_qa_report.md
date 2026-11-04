# Monstrous Manual (TSR 2140) stat blocks: QA report

Source: `D:\ADnD\Core Books\Monstrous Manual.pdf` (391 pages). Result: 187 creature notes in `Monstrous Manual/`, plus 78 images in `Monstrous Manual/images/`. All art was cropped from the PDF.

## Duplicates: most of the book was skipped

The Monstrous Manual (1993) collects the best creatures from MC1, MC2 and the other early compendiums. The vault already has almost all of them, so **only creatures not already in any converted book were added**. The book's index lists roughly 780 creatures; about 590 were skipped as already present.

How duplicates were found: the book's own index (pp. 383-387) was transcribed, and each name was checked against every note in `4 - AI Imported Content`. Anything that matched by name was skipped without reading its page. Pages with possible new creatures were then read, and any creature whose stats matched an existing note was skipped too.

Examples of creatures skipped because they are already in the vault: all the chromatic and metallic dragons, beholder, gauth, spectator, the standard giants, golems, lycanthropes, oozes, snakes, spiders, horses, the standard mammals, Ixitxachitl (MC1, which includes the vampiric variants), Elf (MC1), Guardian Yugoloths (MC2's Guardian Daemons), Satyr and Korred, Xorn, Vampire, Two-headed Troll and the scrags.

**Variants were kept** where the stats differ, e.g. the new trolls (Desert, Spectral, Giant, Ice), Greater Mummy, Giant Skeleton, Dark Naga, Half-Ogre and Ogrillon.

## What was added

- **Gem dragons:** Amethyst, Crystal, Emerald, Sapphire, Topaz.
- **Other dragons:** Brown, Deep, Mercury, Steel, Yellow; Firedrake.
- **Fiends and planar creatures:** Pit Fiend and the three Abishai (Baatezu), Balor and Marilith (Tanar'ri), Red and Blue Slaad, Githyanki, Githzerai, Gith, Gith Pirate, Titan, Phoenix, Nightmare, Moon Dog, Shedu.
- **Beholder-kin:** Death Kiss, Death Tyrant, Hive Mother, Director, Examiner, Lensman, Overseer, Watcher.
- **Giants:** Cyclops (the true one, see below), Desert, Fog, Jungle, Mountain, Reef.
- **Golems:** Bone, Doll, Gargoyle, Glass, and the Stone variants (Caryatid Column, Juggernaut, Stone Guardian).
- **Humanoids:** Derro, Aquatic Elf, Forest Gnome, Giff, Grimlock, Quaggoth, Tabaxi, Tako, Neogi, Manscorpion, Wereraven, Werebat, Sirine, Histachii.
- **Others:** Argos, Aurumvorax, Brain Mole, Broken Ones, Crabman, Deepspawn, Feyr, Gargantua, Gloomwing, Intellect Devourer, Kirre, Living Wall, Mephits, Mold Man, Mudman, Peryton, Su-Monster, Thought-Eater, Xaren, Zaratan, Pech, Tempest and Skriaxit, plus new insects, mammals, small mammals, plants, snakes, spiders, bats and birds.

## Problem found in MC2

MC2's `Cyclops` note (`MC2/cyclops.md`) has AC 3, HD 5 and 270 XP. Those are the **Cyclopskin's** stats, not the Cyclops's. The Monstrous Manual's real Cyclops (AC 2, HD 13, 4,000 XP) was added as `Giant, Cyclops (Monstrous Manual)`. The MC2 note was not changed.

## Summary-table creatures

Several Manual pages print a short table instead of full stat blocks: **Bird** (Boobrie, Eblis, Flightless Bird), **Insect**, **Mammal** and **Mammal, Small**. These notes only have what the table shows (number appearing, AC, movement, HD, THAC0, attacks, damage, morale, XP). Climate, frequency, size and the like are missing. For Mammal, Small, a shared climate, frequency, intelligence, alignment and morale were filled in from the table's footer.

## Things to verify

- **Mephit, Steam:** movement is blank in the table. Stored as "Not printed".
- **Beholder-kin, Death Kiss:** HD printed as "1d8+76 hp". Health is 77-84.
- **Death Tyrant:** HD printed as "45-75 hp", with THAC0 by hit points. Kept as printed.
- **Living Wall:** most stats are "Variable". Health is "64 (base)".
- **Githyanki, Githzerai, Gith Pirate:** stats are "Per class and level".
- **Gem and other new dragons:** the age tables are not included. Only the main stat block is.

## Images

Most creatures have their own art next to the stat block. Wide-table pages have their art on the facing page, and those crops were taken from there (e.g. Baatezu, Beholder-kin, Cat, Small, Mephit, Insect, Living Wall, Mammal, Ooze/Slime/Jelly, Gargantua).

Group members share one image. Some group images show only one of the creatures: Baatezu shows a red abishai, and Beholder-kin shows a line of beholder-kin.

**No image:** where the only art on the spread shows a creature that is not one of the new ones. For example, the Bird page shows an eagle and the Snake page shows a cobra. This applies to Bird, Forest Gnome, Golem (Stone variants), Mammal (Small), Plant (Dangerous), Plant (Intelligent), Snake, Spider and Troll. These 45 notes have no picture.

## Added later

- **Gibberling** (p. 149 of the book, PDF p. 152) was missed in the first pass because the name check matched it to Annual Four's "Gibberling, Brood". It was added on 2026-11-02 after a recheck of the whole index. That recheck found no other missed creatures: the index's "Giant Pig" and "Steppe Pony" only point to rows in the small-mammal and horse tables, which are already covered.
