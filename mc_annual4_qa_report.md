# MC Annual Volume Four (TSR 2173) stat blocks: QA report

Source: `Monstrous Compendium - Annual Volume 4.pdf` (98 pages), with illustrations from `ebook/Monstrous Compendium Annual Volume 4.epub`. Result: 103 creature notes in `MC Annual 4/`, plus 67 images in `MC Annual 4/images/`. One duplicate was skipped (see below).

Pages with several creatures are in folders: Children of the Sea, Clam (Giant), Clockwork Horror, Coral, Fish (Ascallion, Athasian, Deep Ocean, Tropical), Giant (Crag and Fhoimorien), Golem (Gemstone), Octopus (Octo-jelly), Sea Demon, Shadowrath, Skeleton (Variant), Snake (Sewerm and Mahogany Constrictor), and Spyder-Fiend.

## How this book was read

The PDF has no text layer at all, and the EPUB's OCR is poor, so every stat table was read from the page images. Page numbers are PDF page numbers. The PDF and EPUB pages line up exactly (PDF page N = EPUB page N). Pages 1-6 are front matter and 96-98 are the index and covers. These pages continue a creature's text and have no stat table of their own: 19, 21, 28, 34, 36, 41, 46, 54, 65, 69, 72, 79-81, 87, 88 and 91.

## Skipped duplicates

| Annual Four (PDF page) | Already in |
|---|---|
| Shadow, Slow (p. 70) | MC5 `Slow Shadow`: same AC 8, HD 4, THAC0 17, damage 1d4 |

These look similar to existing creatures but are different variants with different stats, so they were kept: Athasian Dolphin (vs. Dolphin), Athasian Shark (vs. Common Shark), Gohlbrorn Bulette (vs. Bulette), Bog Mummy (vs. Mummy), Cerebral Vampire (vs. Vampire), Troll Mutate (vs. Troll), Mud Zombie (vs. zombies), Dust/Spike/Obsidian Skeletons (vs. Skeleton), Grain and Unseelie Nymphs (vs. Nymph), Mahogany Constrictor (vs. constrictors), Squark (vs. Giant Squid), and Octo-jelly/Octo-Hide (vs. Giant Octopus).

## Name changes

- Em-dashes in titles are written as hyphens, e.g. `Dragon, Neutral-Moonstone Dragon`, `Tanar'ri, Lesser-Uridezu (Rat-Fiend)`, `Yugoloth, Lesser-Gacholoth`, `Starfish, Giant-Giant Sunstar`.
- The Neh-thalggu page title "(Brain Collector — Far Realm)" is written `Neh-thalggu (Brain Collector, Far Realm)`.
- Column names were added to group members, e.g. `Clockwork Horror, Copper`, `Fish, Deep Ocean, Angler Fish`, `Spyder-Fiend, Kakkuu`.
- The Giant Clam page has two columns: the giant clam (oyster) and the Carnivorous Scallop. The scallop is `Scallop, Carnivorous` in the `clam_giant` folder.

## Things to verify

- **Fish, Athasian, Shark:** the XP is printed as a dash. Stored as "Not printed".
- **Fish, Tropical, Ray, Electric:** the XP is blank in the book. Stored as "Not printed".
- **Fogwarden:** the table has a second XP line for a giant fogwarden with no value printed.
- **Spyder-Fiend, Raklupis:** the Special Defenses text is cut off in print after "Webs, immunities,".
- **"Nil" THAC0 or AC:** Dream Stalker, Wizshade, Coral (Brain), the Electric Ray and Bloodsipper have THAC0 "Nil", so `to_hit` is blank. Chromatic Mold has AC "Nil".
- **Fish, Tropical:** XP is printed as 1,400 / 2,000 / 3,000 for the Grouper, Morena and Porcupine Fish. The Porcupine Fish (1 HD) at 3,000 XP looks wrong, but is kept as printed.
- **Gibberling, Brood:** THAC0 printed as 16 for 4+2 HD, and XP as 950 (not a standard value). Kept as printed.
- **Kercpa:** the XP line lists values by HD and caster type. Kept as printed.

## Values converted by hand

The normal rules are: AC = 20 - printed AC; to_hit = 20 - THAC0; health uses d8s (N HD = N to 8N; N+X = N+X to 8N+X). These creatures needed manual conversion:

- **AC with several values:** Ammonite (2/8), Anemone (body/tentacle), Blindheim (base), Carapace, Clam and Scallop, Coral (polyp), Dragon-Kin Albino Wyrm (base), Fish, Tropical Morena, Fraal, Human (Amazon, Pygmy), Mercurial (normal [hyper-reality]), Sea Hermit (0/3), Sea Worm, Shade, Shadowrath (Greater), Squark (5/0), Vaati, Worm, Lukhorn (interior).
- **THAC0 by HD:** Bloodsipper (pod denizen), Clockwork Swordsman, Coral Worm, Dragon-Kin Albino Wyrm, Fish, Vurgens, Shade, Snake, Sewerm, Starfish (Sunstar), Vaati, Vampire, Cerebral (+1 for Strength).
- **Health:** Bainligor (2+1 to 10+9), Bloodsipper, Carapace, Clockwork Swordsman (5-10 HD), Coral Worm, Dragon-Kin Albino Wyrm, Fish, Vurgens, Golem (Brass Minotaur, Gemstone, Maggot: printed hp), Human, Amazon (d10 Hit Dice), Shade, Snake, Sewerm and Mahogany Constrictor, Starfish, Vaati.
- **Size:** Bloodsipper, Golem, Maggot and Snake (Sewerm and Mahogany Constrictor) have size ranges, so `size` and `size_detail` hold both.

## Psionics

Coral (Brain), Dolphin (Athasian), Fish (Athasian), Fraal and Squid (Squark) have a printed psionics summary. It is stored in the `psionics` field, as in Annual Three. The `ADnD_AI` layout won't show it unless you add that field.

## Images

Art missing from the EPUB was cropped from the PDF scan for 26 creatures or groups (e.g. Asperii, Bainligor, Darklore, Moonstone Dragon, Hound of Law, Mercurial, Sea Demon, Shade, Squark, Uridezu, Wizshade). Some crops show a little nearby text.

The Spyder-Fiend image comes from its continuation page (p. 81).

The Carnivorous Scallop shares the Giant Clam picture.

**No image** (no art printed in the book): Anemone, Giant Sea; Fish, Tropical (all four); Skeleton, Variant (all three); and Vaati (Wind Duke).
