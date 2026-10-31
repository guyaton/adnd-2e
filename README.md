# ad-d-2e
Used to store / update AD&D 2e Monster Manuals

This repository contains AD&D 2nd Edition monster entries from the Monstrous Compendium volumes (`MC1`–`MC5`) and the Monstrous Compendium Annuals (`MC Annual 1`–`MC Annual 4`). Each one is a Markdown note built to be opened in [Obsidian](https://obsidian.md) and displayed as a stat block by the **Fantasy Statblocks** community plugin.

When everything is set up correctly, a monster note looks like this:

![Sample monster entry rendered with Fantasy Statblocks](Sample%20Monster%20Entry.png)

---

## Repository layout

| Path | Contents |
| --- | --- |
| `MC1` … `MC5`, `MC Annual 1` … `MC Annual 4` | One `.md` note per monster. Some monsters with several variants are grouped into subfolders. |
| `<volume>/images/` | Monster artwork used by the notes in that volume. |
| `Fantasy Statblock. Configjson.json` | The custom **ADnD_AI** layout for Fantasy Statblocks. You need to import it (see below). |
| `Sample Monster Entry.png` | Screenshot of a correctly rendered entry. |
| `*_qa_report.md` | Quality-check notes for each volume. |

Each monster note has a `statblock` code block that names the layout it uses:

````markdown
```statblock
layout: ADnD_AI
name: Aballin
image: images/aballin.jpg
...
```
````

Fantasy Statblocks doesn't come with an `ADnD_AI` layout. **Until you import the layout from the JSON file in this repo, the notes won't render correctly.**

---

## 1. Get the files into an Obsidian vault

1. Clone or download this repository:
   ```bash
   git clone <this-repo-url> adnd-2e
   ```
2. Do one of the following:
   - **Open it as its own vault:** in Obsidian, choose **Open folder as vault** and select the `adnd-2e` folder.
   - **Add it to an existing vault:** copy (or clone) the `adnd-2e` folder into your vault's folder.

Keep each volume's `images` folder where it is. The notes point to their artwork with relative paths like `images/aballin.jpg`.

## 2. Install the Fantasy Statblocks plugin

1. In Obsidian, open **Settings → Community plugins**.
2. If you see **Restricted mode** (or "Safe mode") turned on, click **Turn on community plugins**.
3. Click **Browse**, search for **Fantasy Statblocks** (by Javalent), then click **Install**.
4. Click **Enable** once the install finishes. You can also turn it on later from the **Installed plugins** list.

## 3. Import the ADnD_AI layout

1. Open **Settings** and select **Fantasy Statblocks** in the left sidebar, under *Community plugins*.
2. Scroll down to the **Layouts** section.
3. Click the **Import** button (the upload icon next to *Import from JSON*).
4. In the file picker, go to the folder where you put this repository and select **`Fantasy Statblock. Configjson.json`**.
5. A layout called **`ADnD_AI`** should now show up in the layout list.
   - Don't rename it. Every note in this repo refers to the layout by that exact name (`layout: ADnD_AI`).
   - If you're updating to a newer version of the JSON, delete the old `ADnD_AI` layout first and then import again, so you don't end up with two copies.

## 4. Check that it works

1. Open any monster note, for example `MC Annual 1/aballin.md`.
2. Switch to **Reading view**, or **Live Preview**, which is the default editing mode.
3. The note should look like the screenshot above: the monster's name, size and alignment at the top, its portrait in the corner, then sections for Climate/Terrain, Armor Class, Hit Dice, Morale, XP Value and so on.

---

## Troubleshooting

| What you see | Likely cause and fix |
| --- | --- |
| A grey code block of plain text instead of a stat block | Fantasy Statblocks isn't installed or enabled. Repeat step 2. |
| A basic 5e-style stat block, or an error mentioning the layout | The `ADnD_AI` layout isn't imported or has been renamed. Repeat step 3 and make sure the name is exactly `ADnD_AI`. |
| The stat block renders but the portrait is missing | The `images` folder for that volume was moved or isn't in the vault. Put it back next to the notes. |
| Changes don't show up after importing the layout | Close and reopen the note, or reload Obsidian with the **Reload app without saving** command. |
| Some fields show `undefined` or `-` | That field is blank in the note's `statblock` block. This is normal for entries where the source book doesn't list the stat. |
