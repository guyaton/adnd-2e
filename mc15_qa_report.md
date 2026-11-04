# MC15 Ravenloft Appendix II - Children of the Night (TSR 2139) stat blocks: QA report

Source: `MC 10 Monstrous Compendium Ravenloft II.pdf` (70 pages; despite the filename, this is MC15), with illustrations from `ebook/MC 15 Monstrous Compendium Ravenloft II.epub`. Result: 20 creature notes in `MC15/`, plus 20 images in `MC15/images/`.

## What this book is

Children of the Night is a book of **unique named villains**, not creature types. Each entry is one individual, e.g. `Vampire, Eastern (Mayonaka)` or `Medusa (Althea)`. The base creature name comes first and the villain's name in brackets, as printed. Because each is a specific individual with its own stats, none were treated as duplicates of the generic creatures already in the vault.

## How this book was read

The PDF has no text layer, but this EPUB's OCR is clean, so stat blocks were taken from the EPUB text and spot-checked against the page scans (Jacqueline Montarri, Jahed and Mayonaka were checked line by line). Page numbers are PDF page numbers; EPUB page N is PDF page N+1. Pages 1-7 are covers, credits, introduction and an essay; 64 is "Calculating Experience Points"; 65-70 are art and covers. Every villain has 2-4 pages of story and adventure hooks after the stat block; those are not in the notes.

## Things to verify

- **Human, Cursed (Jacqueline Montarri):** THAC0 "15 (12) or better" and XP "Varies (2,000+)".
- **Human, Voodan (Chicken Bone):** THAC0 "See below" (it depends on his rituals).
- **Lycanthrope, Weretiger (Jahed):** frequency is "Very rare" and organization "Pack", unlike the others. The Special Attacks cell holds his rear-claw rake damage (2-5/2-5).
- **Vampire, Eastern (Mayonaka):** THAC0 "11 (8); (5 with katana)" and two damage sets (touch or katana).
- **Brain, Living:** movement is "Special".
- **Thrax (Paiik):** his psionics summary is stored in the `psionics` field.
- Hit points are printed for every villain (e.g. "8+3 (46 hp)"), so `health` holds the exact value instead of a range.

## Images

All art comes from the EPUB except the Ice Queen (Spectre, Jezra Wagner), which was cropped from the PDF because the EPUB has no image for her page. Every note has an image.
