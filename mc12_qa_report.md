# MC12 Dark Sun Appendix - Terrors of the Desert (TSR 2405) stat blocks: QA report

Source: `MC 12 Monstrous Compendium Dark Sun - Terrors of the Desert.pdf` (103 pages), with illustrations from `ebook/MC 12 Monstrous Compendium Dark Sun - Terrors of the Desert.epub`. Result: 91 creature notes in `MC12/`, plus 57 images in `MC12/images/`. One creature was skipped as a duplicate.

Folders: Animal (Herd), Animal (Household), Antloid (Desert), Brambleweed, Cat (Psionic), Drake (Athasian), Elemental (Athasian), Giant (Athasian), Golem (Athasian), Insect Swarm (Athasian), Plant (Carnivorous, Athas), Sand Bride, and Silt Horror.

## How this book was read

The PDF's text layer is poor, so every stat table was read from the page images. Page numbers are PDF page numbers; EPUB page N is PDF page N+1. Pages 1-7 are covers, credits and the "How to Use This Book" terrain tables; 98-103 are blank or covers. These pages are introductions or continue a creature's text: 9, 11, 13, 15, 19, 26, 27 (Drakes, general), 34, 35 (Elementals, general), 47, 48 (Golems, general), 61, 63, 65, 69, 73, 75, 79, 81, 89 and 93.

## Skipped duplicates

| MC12 entry (PDF page) | Already in |
|---|---|
| Kirre (p. 57) | Monstrous Manual `Kirre` (same AC, HD, damage and XP) |

Kept as separate creatures:
- **Thrax** (generic, 2,000 XP) is different from MC15's named villain `Thrax (Paiik)` (4,000 XP).
- **Roc, Athasian**, **Halfling, Renegade**, **Mul, Wild**, **Kank, Wild** and the Athasian elementals, golems, giants and insect swarms are Dark Sun versions with their own stats.

## Psionics

Most Dark Sun creatures have a psionics summary. It is stored in the `psionics` field (level, disciplines/sciences/devotions, attack/defense modes, score and PSPs). Creatures printed as "Psionics: Nil" have `psionics: Nil`. The `ADnD_AI` layout won't show this field unless you add it.

## Things to verify

- **Elemental, Athasian, Greater Air:** the Armor Class row is blank. Stored as "Not printed".
- **Pulp Bee:** the Armor Class row is blank. Stored as "Not printed". XP is printed as "2000".
- **Brambleweed, Tree:** THAC0 printed as a dash.
- **Esperweed:** nearly every stat is "Nil" (it is a plant used for its psionic boost).
- **Dune Runner, Banshee (Dwarf):** most stats are "As in life".
- **Villichi:** AC, HD, THAC0, morale and XP all "Varies" (by level).
- **Silt Runner:** morale printed as "Average (1-10)". Kept as printed.
- **Rasclinn:** psionics printed as "Special".
- **Athasian Drakes:** HD are printed with fixed hit points (e.g. "25+9 (170 hit points)"), so `health` holds the exact value.

## Values converted by hand

- **AC with two values:** B'rohg 7 (10), Cha'thrang (shell/underbelly), Erdland 7 (9), Mul 8 (10), Pyreen 0 (10), Razorwing 3/6, Sand Cactus (body/needles).
- **THAC0 by HD:** Cloud Ray, Athasian elementals (greater and lesser), Sand Cactus, Scrab, Tohr-kreen.
- **Health:** Household animals (fractional HD), Brambleweed and Burnflower (per 10' square / per patch), Cloud Ray (12+7 to 24+7), Athasian elementals, insect swarms (per 10 or 15 insects), Pyreen (16-20 HD), Sand Cactus, Scrab, Tohr-kreen.

## Images

All art comes from the EPUB. Many Dark Sun EPUB images include the page's "Dark Sun" header banner above the picture; this was left as is. The B'rohg image also included its stat table, so it was trimmed to the picture. Groups share one picture per page. Every note has an image.
