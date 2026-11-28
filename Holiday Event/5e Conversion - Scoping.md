---
title: "Yippee-Ki-Yule: 5e Conversion Scoping"
system: D&D 5e (planned)
status: on-hold
tags:
  - christmas-event
  - dnd5e
  - planning
---

# Yippee-Ki-Yule: 5e Conversion Scoping

> [!abstract] Goal
> Run the event in **both** AD&D 2nd Edition and D&D 5e. Nothing has been converted yet. This note records the effort estimate and the decisions still to make.

**Links:** [[Yippee-Ki-Yule - Core Design]] · [[Party Dream Sheets]] · [[Christmas NPCs]] · [[Random Encounters]]

---

## Decisions to Make First

- [ ] **2014 or 2024 rules?** This affects nearly everything: species, backgrounds, Weapon Mastery, and how rests work.
- [ ] **Same levels as in 2e?** Is Ambrosis level 5 or 6?
- [ ] **Henchmen (Xarles, Umana, Selena): full characters or sidekicks?**
- [ ] **Does the 5e version need to be ready this Christmas?** If so, do the characters and the rest rules first, then convert the floors in the order they're played.
- [ ] **How to keep both editions** (see the last section). Recommended: one set of notes with `[!2e]` / `[!5e]` callouts.

**Suggested pilot:** convert **Ambrosis** (the hardest character) and **Floor 1** (to settle the callout format) before committing to the rest.

---

## 1. Converting the Characters (Medium)

Mostly mechanical. The same 3–18 ability scores carry over, the sheets already use ascending AC, and the HP method (max at 1st, average after, plus Con) is exactly the 5e method.

What changes for every character:
- **THAC0 becomes an attack bonus** (proficiency + ability modifier).
- **Five saving-throw categories become six ability saves.**
- **Nonweapon proficiencies become skills.** Languages carry over.
- **HP goes up.** 5e modifiers start at 12 instead of 15, and wizards and thieves get bigger hit dice (d4 → d6, d6 → d8).

| Character | 2e | 5e | Difficulty |
|---|---|---|---|
| Grommond | Dwarf Fighter 6 | Fighter 6. Extra Attack settles the 3/2-attacks question. | Easy |
| Xarles, Selena | Fighter 4 | Fighter 4 (or Warrior sidekicks) | Easy |
| Umana | Cleric 4 | Cleric 4 (War or Light domain), or a Spellcaster (healer) sidekick. The Wis bonus spells disappear. | Easy |
| Baki | Wizard 5 | Wizard 5. Still gets *Fireball*. His *A Second Cup* ticket overlaps 5e's Arcane Recovery, so the ticket needs a new power. | Easy, plus a ticket rewrite |
| Isla | Druid 6 | Druid 5 or 6. She gets **Wild Shape at 2nd level**, which breaks the "no Shapechange until 7" note. *Call Lightning* still works. | Medium |
| Ambrosis | Illusionist 4 / Thief 5 | **Rogue (Arcane Trickster) 5–6** is the clean fit: illusion spells plus thief skills. A real multiclass would be messy. His 120-point thief worksheet becomes Expertise. | Hardest |

**Other pieces:**
- **Sheets are the biggest job.** The 2e sheets are the TSR form with handwriting laid over it. 5e needs a new background page: the free official sheet, or a custom one in the same teal and blue.
- **The spells page is small.** In 5e, slots go by class level with no Wis bonus, and "free casting" is already close to how 5e casting works. The generator in `Character Sheets/_build/` needs only a few changes.
- **Tickets and gifts need numbers redone.** "+2 to hit" or "+3 vs. illusions" become advantage or DCs. The *Wand of Frost* conflicts with 5e's *Cone of Cold* (5th level, 8d8), so it needs a new name or new damage.

---

## 2. Skill Checks, Saves and Monsters (Medium–Large)

Counted across the 55 event notes (November 2026):

| 2e mechanic | Mentions | 5e replacement |
|---|---|---|
| "Save vs." | ~38 | Ability saving throw with a DC |
| Ability checks | ~50 | Skill check with a DC |
| Thief-skill percentages | ~49 | Thieves' tools / Stealth / Sleight of Hand checks |
| Morale | ~62 | 5e has no built-in morale: use triggers ("flees at half HP") |
| Other percentages | ~44 | Case by case |

- **Many scenes get better with skills:** Insight against Hans posing as a hostage, Investigation for Kevin's traps, Persuasion for helping Jack, **passive Perception** for spotting the Elf on the Shelf.
- **Use a standard DC scale (10 / 15 / 20)** to keep it quick.
- **Monsters are the real work.** Only 5 formal stat blocks, but stats for many others are written into the floor notes (about 50 Hit Dice and 18 THAC0 references). All need 5e stat blocks and CRs. The Fantasy Statblocks plugin already shows the 5e layout.
- **Encounter balance is the biggest risk.** Seven 5e characters at level 4–6 have far more actions per round than seven 2e characters. Krampus at 70 HP would go down in about two rounds. Bosses need legendary actions and fresh math.

---

## 3. Hirelings and Sidekicks

- **The torchbearers have little to do in 5e.** Three of the four PCs have darkvision, and *Light* is a cantrip. They're hostages for most of the event, so as sidekicks they'd only fight from Gruber's Vault to the roof.
- **The henchmen make better sidekicks.** Xarles and Selena as **Warrior** sidekicks, Umana as a **Spellcaster (healer)** sidekick. Rules are in the 5e Essentials Kit, free on D&D Beyond. This shrinks the action-economy problem, and a sidekick sheet is about half a page. Players can still run them.
- **Serah, Lerdo, Vladimir and Stavros** stay hirelings in name, with Commoner stats as hostages. Their story is the same in both versions.

---

## 4. Rests and the Midnight Clock

- **Rename "turns."** In 5e a turn is one creature's go in a combat round, not 10 minutes. About 133 references. Use something like **"10-minute tick"**; the 100-unit clock stays.
- **A long rest is far stronger in 5e.** A 2e rest mostly brings back spells (natural healing is about 1 HP a day). A 5e long rest restores all HP, all spells, and some or all Hit Dice. The Floor 20 stop becomes worth much more. It could stay at 12 ticks or cost more.
- **Short rests are new, and 5e expects them.** Fighter abilities, Hit Dice healing, Arcane Recovery and Wild Shape recharge on them. A 1-hour short rest costs **6 ticks in the tower, or about 2 on the train**. With about 80 of 100 ticks used, the party can afford only 2–3 short rests: good tension, but the design must say so.
- **Spells that touch the clock:**
  - Rituals add 10 minutes, so 1 tick each.
  - At Wizard 5, Baki can cast ***Leomund's Tiny Hut*** (a safe rest anywhere) and ***Catnap*** (a 10-minute short rest). Decide whether Kevin's demiplane allows them.

---

## Keeping Both Versions

About 83,000 words across 55 notes. An estimated **70–80% is edition-neutral**: read-aloud text, NPCs, maps, tickets, the soundtrack.

- **Option A, copy the folder.** Fastest start, but every story fix has to be made twice, and the versions drift apart.
- **Option B, one set of notes (recommended).** Rules go in `[!2e]` and `[!5e]` callouts inside the shared notes. A CSS snippet hides one edition on export, giving two PDFs from one source. Character sheets and stat blocks are separate files for each edition.

## Effort Summary

| Work | Size |
|---|---|
| Character conversions (7) | Medium |
| New 5e sheet backgrounds | Large if custom-styled; small with the official sheet |
| Spells page and tickets | Small |
| Skill checks and saves across all floors | Medium–Large |
| Monster stats and encounter balance | **Large** (needs the most judgment) |
| Rest and clock rules | Small to write; needs decisions first |
| Setting up two editions (Option B) | Medium, done once |
