# MC19 Planescape Monstrous Compendium Appendix II stat blocks: QA report

Source: `MC 19 - Planescape Monstrous Compendium 2.pdf` (130 pages), with some illustrations from `ebook/MC 19 - Planescape Monstrous Compendium 2.epub`. Result: 60 creature notes in `MC19/`, plus 60 images in `MC19/images/`.

Folders: Eladrin, Guardinal, Rilmani, and Tanar'ri.

**Product code:** the scan doesn't show the TSR product number (no credits-page code, and the back cover only has the ISBN). Notes use the ISBN instead: `MC19, ISBN 0-7869-0173-X`.

## How this book was read

The PDF is full-page scans. The EPUB's OCR was used as a draft and every stat table was checked against the page images. Page numbers are PDF page numbers; EPUB page N is PDF page N+1. Pages 1-6 are covers, contents and encounter tables; 29 (Eladrin), 43 (Guardinal) and 85 (Rilmani) are general introductions; 129-130 are the index and back cover.

**Psionics:** Dhour, Hollyphant and Observer have a psionics summary. It's kept in the `psionics` field, which the `ADnD_AI` layout doesn't display.

## Skipped duplicates

The book says it includes "selected revised entries from older sources". These creatures are already in the vault with the same AC and movement; the differences are listed below (mostly XP and damage). The existing notes were kept:

| MC19 entry (PDF page) | Already in | What changed in MC19 |
|---|---|---|
| Balaena (p. 15) | MC8 | Damage 2d10 (MC8: 1-10) |
| Mortai (p. 67) | MC8 | XP 25,000 (MC8: 58,500); damage 10d6 |
| Noctral (p. 69) | MC8 | XP 3,000 (MC8: 7,000) |
| Retriever (p. 83) | MC14 | HD 10+10 (MC14: 10), THAC0 9, XP 15,000 (MC14: 7,000) |
| Simpathetic (p. 95) | MC11 | HD 1-4 hp (MC11: 4 hp), damage 1d2 (MC11: 1-4), XP 175 (MC11: 650) |
| T'uen-rin (p. 105) | MC8 | XP 28,000 (MC8: 150,000) |
| Vaporighu (p. 118) | MC8 | Damage 1d6+2/1d6+2 (MC8: 1-6), XP 14,000 (MC8: 24,000) |

If you'd rather have the revised Planescape values, those MC8, MC11 and MC14 notes are the ones to edit.

## Kept although the name is close to one already in the vault

- **Bloodthorn:** a different plant from Annual 2's `Plant, Dangerous, Bloodthorn` (HD 3-8 here vs. 10, AC 3 vs. 4).
- **Arcane:** not the same as `Head, Arcane`.
- **Reave:** not the same as MC10's `Reavers`.

## Things to verify

- **Incantifer:** HD is "9d4+18 to 9d4+26" (a 9th- to 18th-level mage); health is set to 27-62, the range of the printed dice.
- **Merkhant, Prolonger, Rager:** stats vary by class and level. The values in brackets are the book's typical example.
- **Monster of Legend:** a template; the bracketed values are the book's example legendary sphinx.
- **Shadowdrake:** stats grow with age like a dragon's; `(base)` values are given, and XP runs from 3,000 (hatchling) to 18,000 (great wyrm). The age table is in the book.
- **Maurezhi:** HD 5 to 5+8 (it gains hit points as it feeds); XP 2,000 unimproved, 6,000 mature.
- **Yochlol:** AC and attacks differ by form (amorphous, spider, humanoid).
- **Razorvine:** 5 hp per vine; XP 35 per vine; morale "None".
- **Observer:** AC -2 for the body, 2 for the eyestalks.
- **Darkweaver:** AC -4 (4) and MR 50% (10%); the second values apply in light.

## Images

About a third of the art comes from the EPUB; the rest was cropped from the PDF scans. Most of this book's art is full-page and printed behind the text, so many crops include some text.

- The Equinal and Leonal share one picture.
- The Eladrin Tulani picture comes from the full-page eladrin art on p. 38, which isn't labelled; it's most likely the tulani.
- The Ghostlight picture is a full-page scene from its second page.
