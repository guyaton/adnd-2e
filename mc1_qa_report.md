# MC1 stat blocks: QA report

Source: tsr02102_-_MC_1_Monstrous_Compendium_text.pdf (an OCR scan). Result: 247 creature notes in `mc1_bestiary/`, one folder per page that has several creatures.

Entry names below are the page titles used while parsing (for example `bear` means the `bear/` folder). Page numbers are PDF page numbers; the book has none printed.

## What was fixed by hand

- Umber Hulk and Vodyanoi (p. 132): the table runs into body text, so both were entered from the scan. XP values (4,000 and 2,000) came from the OCR, not read directly: verify.
- Giant Toad, Fire Toad, Ice Toad, Poisonous Toad (p. 128): names taken from the scan header in column order.
- Generic table headers were renamed so every name is unique (for example "Giant" became "Giant Owl", "Winter" became "Winter Wolf", "Ore" became "Orc").

## Pages with no creature stat block (skipped)

- PDF p. 30: Dragons (general information)
- PDF p. 31: Dragons (general information)
- PDF p. 44: Elemental, Generic Information (general information)
- PDF p. 84: Lycanthrope, General (general information)
- PDF p. 63: Golem, General (overview only)
- PDF p. 145: blank monster form

## Cells that were missing or garbled: now resolved

The wiki (adnd2e.fandom.com) could not be fetched from here, so every cell below was checked against the MC1 PDF page images instead and corrected in the notes (53 field changes across 34 creatures):

- Black Bear, Brown Bear: organization = Family
- Bookworm: no_appearing = 1-2 (10-40)
- Giant Centipede, Huge Centipede: damage_per_attack = Nil
- Cockatrice: damage_per_attack = 1-3
- Dragon, Red; Dragon, White: activity_cycle = Any
- Ghast: no_appearing = 1-6
- Gnoll: special_attacks = Nil
- Medusa, Greater Medusa: damage_per_attack = 1-4
- Mind Flayer: activity_cycle = Any, damage_per_attack = Special
- Mud-man: damage_per_attack = Special
- Nixie: damage_per_attack = By weapon type
- Piercer: damage by HD (1-6 / 2-12 / 3-18 / 4-24), xp_value 35 / 65 / 120 / 420 by HD
- Pseudodragon: no_appearing 1 (50% chance of 1-8 in nests), AC 2 (ascending 18), damage 1-3 + special
- Common Rat 1, Normal Skunk 1, Giant Skunk 1-6
- Manta: THAC0 by HD (13 / 11 / 9), attacks 1 tail or 1 bite, damage 3-12 (bite) or 2-20 (sting), XP 3,000 to 6,000 by HD
- Pungi: 1-12 attacks at 1-4 each, XP 975
- Sting: damage 1-3, XP 120
- Fire Toad: 4+1 HD (health 5-33), damage Variable, treasure C
- Ice Toad 3-12, Poisonous Toad 2-5, Giant Toad activity cycle Any
- Ixitxachitl: damage 3-12 (1d10 + 2), XP by type (35 to 420, vampiric 270)
- Treant: damage Variable, XP 7 HD: 2,000 (+1,000 per Hit Die)
- Vampire: damage 5-10, XP Western 3,000 / Eastern 4,000
- Wight 1-4, Winter Wolf 1 attack for 2-8, Wraith 1-6, Yeti activity cycle Day

### Still open

- Rakshasa, Greater: xp_value is blank because the book prints XP values only for the standard rakshasa (4,000; ruhk 7,000; rajah 7,000; maharajah 10,000), with none for the greater one.
- Umber Hulk and Vodyanoi XP (4,000 and 2,000) came from the OCR and are still unconfirmed.

## Complex values kept as printed

Armor class, THAC0 and morale cells with extra text (for example "17 (4 HD) or 15 (5 and 6 HD)") keep the printed text; the plain numbers inside were converted. Entries:

air_earth_elementals, bat, beholder, bookworm, bugbear, carrion_crawler, cats_great, cave_fisher, centaur_sylvan, chimera, dragon_black, dragon_blue, dragon_brass, dragon_bronze, dragon_copper, dragon_gold, dragon_green, dragon_red, dragon_silver, dragon_turtle, dragon_white, elephant, elf, fire_water_elementals, ghost, giant_fire, giant_frost, giant_hill, giant_stone, giant_storm, gnolls, gnome, goblin, halfling, hobgoblin, hornet, horse, hydra, kobold, lich, lizard_man, lycanthrope_seawolf, men, mind_flayer, minotaur, mud_man, ore, owlbear, piercer, puddings_deadly, ray, remorhaz, selkie, shadow, skeleton, treant, umber_hulk, wolf, yuan_ti, zombie

## Health field (hit dice to hp range)

Rule: every die is a d8, so N HD = N to 8N (16 HD = 16-128, 2+2 = 4-18). Hit points printed in the book are used as printed.

### Left blank (no usable hit dice)

- Brownie: hit_dice "Vz"
- Jackal: hit_dice "V 2 (1-4 hp)"
- Kobold: hit_dice "Vz (1-4 hit points)"
- Demilich: hit_dice "See below"
- Adventurers: hit_dice "Varies"
- Knights: hit_dice "Varies"
- Mercenary Soldiers: hit_dice "Varies"
- Sailors: hit_dice "Varies"
- Slavers: hit_dice "Varies"
- Thieves/Thugs: hit_dice "Varies"
- Wizards: hit_dice "Varies"
- Common Rat: hit_dice "V<"

### Assumptions made

- Air Elemental: "8, 12, or 16" -> 8-64 / 12-96 / 16-128 (several HD options)
- Earth Elemental: "8, 12, or 16" -> 8-64 / 12-96 / 16-128 (several HD options)
- Cattle: "1-4" -> 1-32 (read as a range of 1 to 4 HD)
- Huge Bat (mobat): "4-6" -> 4-48 (read as a range of 4 to 6 HD)
- Eye of the Deep: "10-12" -> 10-96 (read as a range of 10 to 12 HD)
- Bookworm: "1/4 (2 hit points)" -> 1-2 (1/4 HD read as a d2)
- Pyrolisk: "6 4*2" -> 6-48 (OCR junk after number ignored)
- Dragon, Black: "12 (base)" -> 12-96 (printed note "(base)" ignored)
- Dragon, Blue: "14 (base)" -> 14-112 (printed note "(base)" ignored)
- Dragon, Brass: "12 (base)" -> 12-96 (printed note "(base)" ignored)
- Dragon, Bronze: "14 (base)" -> 14-112 (printed note "(base)" ignored)
- Dragon, Copper: "13 (base)" -> 13-104 (printed note "(base)" ignored)
- Dragon, Gold: "16 (base)" -> 16-128 (printed note "(base)" ignored)
- Dragon, Green: "13 (base)" -> 13-104 (printed note "(base)" ignored)
- Dragon, Red: "13 (base)" -> 13-104 (printed note "(base)" ignored)
- Dragon, Silver: "15 (base)" -> 15-120 (printed note "(base)" ignored)
- Dragon Turtle: "12-14" -> 12-112 (read as a range of 12 to 14 HD)
- Dragon, White: "11 (base)" -> 11-88 (printed note "(base)" ignored)
- Oliphant: "8+4(10+5)" -> 12-68 (extra printed text ignored)
- Fire Elemental: "8, 12, or 16" -> 8-64 / 12-96 / 16-128 (several HD options)
- Water Elemental: "8, 12, or 16" -> 8-64 / 12-96 / 16-128 (several HD options)
- Giant, Cloud: "16+2-7 hit points" -> 18-135 (read as 16 HD plus 2-7 hp)
- Giant, Fire: "15+2-5 hit points" -> 17-125 (read as 15 HD plus 2-5 hp)
- Giant, Frost: "14+1-4 hit points" -> 15-116 (read as 14 HD plus 1-4 hp)
- Giant, Hill: "12+1-2 hit points" -> 13-98 (read as 12 HD plus 1-2 hp)
- Giant, Stone: "14+1-3 hit points" -> 15-115 (read as 14 HD plus 1-3 hp)
- Giant, Storm: "19+2-7 hit points" -> 21-159 (read as 19 HD plus 2-7 hp)
- Goblin: "1-1" -> 1-7 (read as dice minus 1 hp)
- Stone Golem: "14 (60 hp)" -> 14-112 (printed note "(60 hp)" ignored)
- Iron Golem: "18 (80 hp)" -> 18-144 (printed note "(80 hp)" ignored)
- Flesh Golem: "9 (40 hp)" -> 9-72 (printed note "(40 hp)" ignored)
- Clay Golem: "11 (50 hp)" -> 11-88 (printed note "(50 hp)" ignored)
- Hobgoblin: "14-1" -> 13-111 (read as dice minus 1 hp)
- Hydra: "5-12" -> 5-96 (read as a range of 5 to 12 HD)
- Lernaean: "5-12" -> 5-96 (read as a range of 5 to 12 HD)
- Pyrohydra: "7-8" -> 7-64 (read as a range of 7 to 8 HD)
- Cryohydra: "5-8" -> 5-64 (read as a range of 5 to 8 HD)
- Lich: "11 +" -> 11-88 (OCR junk after number ignored)
- Lycanthrope, Weretiger: "6 4*2" -> 6-48 (OCR junk after number ignored)
- Lycanthrope, Werewolf: "4 4*3" -> 4-32 (OCR junk after number ignored)
- Piercer: "1-4" -> 1-32 (read as a range of 1 to 4 HD)
- Manta: "8-11" -> 8-88 (read as a range of 8 to 11 HD)
- Remorhaz: "7-14 13 (7-8 HD), 11 (9-10 HD), 9 (11-12 HD)," -> 7-112 (read as a range of HD; rest of text ignored)
- Animal Skeleton: "1-1" -> 1-7 (read as dice minus 1 hp)
- Treant: "7-12" -> 7-96 (read as a range of 7 to 12 HD)
- Worg/Dire: "3+3/4+4" -> 6-27 / 8-36 (two creatures separated by /)
- Yuan-ti: "6-9" -> 6-72 (read as a range of 6 to 9 HD)

## Summaries (description, combat, habitat_society, ecology)

Added to the 89 creatures whose Special Attacks or Special Defenses say "See below" or "Special", plus Large Spider and the earlier Aerial Servant (91 in total). They are condensed paraphrases written from the scan text, not the book's wording, and are limited to what the page said. Check these against the book before you rely on them:

- Clay Golem and Iron Golem: the scan's columns are interleaved, so some weapon and spell effects were only partly legible. The notes say so.
- Monster Zombie: the book has no separate text for it, so the summary applies the standard zombie rules.
- Elf: the combat text is cut off at the end of the scan page, so it may be missing details.
- Efreeti: parts of its combat text were garbled in the scan.
- Dragons: breath weapon damage and spell counts by age are in the book's age table and were not copied; only the abilities are summarized.
- Halflings (Hairfoot, Stout, Tallfellow) share one combat summary, as in the book.

## Images

Each note has an `image` field with a relative path to a JPEG (700 px wide) in `images/`: `images/name.jpg` for top-level notes and `../images/folder.jpg` for notes inside a group folder. Creatures on the same page share one image. 181 notes use the illustration extracted from the EPUB (EPUB page N = PDF page N+1); 28 use illustrations cropped from the PDF scan where the EPUB had none (Aerial Servant, Bear, Beholder, White Dragon, the four Elementals, Elephant, Genie, Stone Giant, both Golem pages, Hyena). A few of those crops contain two stacked pictures. No image: Bat, Invisible Stalker, Men, Ray and Snake, whose pages have no illustration.

## Morale

The `morale` field holds the word and the number together, for example `Steady (11-12)`. The cells below were garbled, split across two lines or had no word in the scan, so I cleaned or inferred them: please check them against the book.

- Air Elemental: `8-12 HD: Champion (15-16); 16 HD: Fanatic (17)`
- Dragon, Black: `Fanatic (16 base)`
- Dragon, Blue: `Fanatic (16 base)`
- Dragon, Brass: `Fanatic (17 base)`
- Dragon, Bronze: `Fanatic (17 base)`
- Dragon, Copper: `Elite (16 base)`
- Earth Elemental: `8-12 HD: Champion (15-16); 16 HD: Fanatic (17)`
- Fire Elemental: `8-12 HD: Champion (15-16); 16 HD: Fanatic (17)`
- Giant, Frost: `Very Steady (13-14)`
- Giant, Stone: `Champion (16)` (printed only as "16"; word inferred (Champion))
- Gorgimera: `Elite (13-14)`
- Lizard King: `Champion (16)` (printed only as "16"; word inferred (Champion))
- Lizard Man: `Elite (14)` (printed only as "14"; word inferred (Elite))
- Oliphant: `8+4 HD: Unsteady (7); 10+5 HD: Average (10)`
- Water Elemental: `8-12 HD: Champion (15-16); 16 HD: Fanatic (17)`
- Wyvern: `Very Steady (14)`
- Yuan-ti: `Elite (14) / Champion (15)`
- Men types: `Varies` (no number printed). Several entries print `Special` (Bookworm, Carrion Crawler, Ghost, Mud-man, the four Puddings, Shadow, Skeletons, Zombies); a few print a number plus Special (Mind Flayer, Minotaur, Owlbear).
