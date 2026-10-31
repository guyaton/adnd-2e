# MC3 Forgotten Realms Appendix (TSR 2104) stat blocks: QA report

Source: `MC 3 Monstrous Compendium Forgotten Realms Appendix.pdf` (70 pages). There is no EPUB for this book yet, so all art was cropped from the PDF. Result: 60 creature notes in `MC3/`, plus 39 images in `MC3/images/`. Twelve duplicates were skipped (see below).

Pages with several creatures are in folders: Beholder-kin, Dinosaur, Dinosaur (Aquatic), Maedar, and Vulture. New dinosaurs go in `MC3/dinosaur/`, separate from Annual Two's dinosaur folder.

## How this book was read

The PDF has a text layer, but it drops many stat rows, so every stat table was read from the page images. Page numbers are PDF page numbers. Pages 1-3 are covers and an encounter table, 18-19 are dinosaur introduction pages, 30-33 are dinosaur art pages, and 66-70 are blank or covers. These pages continue a creature's text: 7, 35, 37, 51, 55 and 61.

## Skipped duplicates

MC3 is an early book, and many of its creatures were reprinted in later books that are already converted. These were skipped because the stats match:

| MC3 entry (PDF page) | Already in |
|---|---|
| Ascallion (p. 4) | Annual 4 `Fish, Ascallion` (3 notes) |
| Asperii (p. 5) | Annual 4 `Asperii` |
| Bunyip (p. 12) | Annual 3 `Bunyip` |
| Burbur (p. 13) | Annual 3 `Burbur` |
| Firenewt (p. 46) | Annual 3 `Firenewt` |
| Firestar (p. 47) | Annual 4 `Firestar` |
| Meazel (p. 49) | Annual 3 `Meazel` |
| Pleistocene Animals (p. 50: Axebeak, Baluchitherium, Megatherium, Phororhacos, Woolly Rhino, Titanothere) | Annual 2 `Pleistocene Animal` folder |
| Strider, Giant (p. 56) | Annual 3 `Strider, Giant` |
| Thessalmonster (p. 60: four creatures) | Annual 3 `Thessalmonster` folder |
| Vurgens (p. 63) | Annual 4 `Fish, Vurgens` |
| Web, Living (p. 64: Living and Memory) | Annual 3 `Web, Living` folder |
| Dinosaurs reprinted in Annual 2: Allosaurus, Archelon, Brontosaurus, Ceratosaurus, Compsognathus, Dimetrodon, Dinichthys, Euparkeria, Gorgosaurus, Mosasaurus, Nothosaurus, Plateosaurus, Plesiosaurus, Struthiomimus, Tanystropheus, Temnodontosaurus, Teratosaurus, Trachodon | Annual 2 `Dinosaur` and `Dinosaur, Aquatic` folders |

Similar but different creatures were kept: Svirfneblin (vs. Gnome), Beholder-kin (vs. Beholder), the oriental "lung" dragons, and Faerie Dragon (vs. the faerie sprites).

## Problem found in Annual Two

Two Annual Two dinosaur notes have the wrong stats. Each is a copy of a different dinosaur:

- `MC Annaul 2/dinosaur/dinosaur_iguanodon.md` has the Dimetrodon's stats (HD 3 to 5, 65-175 XP).
- `MC Annaul 2/dinosaur/dinosaur_monoclonius.md` has the Euparkeria's stats (HD 1+1, 35 XP).

So the vault had no correct Iguanodon or Monoclonius. MC3 has both, so they were added as `Dinosaur, Iguanodon (MC3)` and `Dinosaur, Monoclonius (MC3)`. The Annual Two notes were not changed.

## Things to verify

- **Pentaceratops:** the Special Attacks cell is blank in the book. Stored as "Not printed".
- **Darkenbeast:** THAC0 printed as 19 for 5+5 HD (15 would be normal). Kept as printed.
- **Anchisaurus:** 2 HD but 2,000 XP, and THAC0 16. Kept as printed.
- **Revenant:** THAC0 "13 (base)" for 8 HD. Kept as printed.
- **Spectator:** HD printed as "4+4 hit points". Health is entered as 8-36 (4d8+4).
- **Glyptar:** THAC0 "See below", so `to_hit` is "See below".
- **Dracolich:** most stats are "As per former dragon type".
- **Lung dragons and Faerie Dragon:** the age tables (AC, MR, XP and breath by age) are not included. Only the main stat block is.

## Values converted by hand

- **AC with several values:** Beholder-kin (Spectator body/eyes, Gauth 0/2/7), Belabra (head/tentacles), Cloaker, Death (Crimson), Faerie Dragon (invisible), Monoclonius, Pentaceratops, Stegosaurus, Dacentrurus, Kentrosaurus, Styracosaurus and Triceratops (front/rear), Svirfneblin ("2 and better"), Wemic (males/females).
- **THAC0 by HD:** Gauth, Bichir, Camptosaurus, Sull.
- **Health:** Gauth (6+6 to 9+9), Bichir (5 to 7 HD), Crawling Claw (2-4 hp), Brachiosaurus (36 HD), Camarasaurus, Camptosaurus (1-3 HD), Faerie Dragon (1-16 hp by age), Glyptar (1-4 hp), Sull (3 to 6 HD).

## Images

Every image was cropped from the PDF. Most single-creature pages have the art next to the stat table. The new dinosaurs' art comes from the four labelled art pages (pp. 30-33). Some crops show a little nearby text or a neighbouring drawing.

**No image** (no art printed for them in this book): Anchisaurus, Brachiosaurus, Camarasaurus, Cetiosaurus, Dacentrurus, Dilophosaurus, Diplodocus, Elasmosaurus, Kentrosaurus, Mamenchisaurus, Massospondylus, Ornitholestes, Paleocinthus, Pentaceratops, Podokesaurus, Pterosaurus, and the three Vultures.

The Beholder-kin picture shows the Spectator; the Gauth has the same picture.
