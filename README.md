# Starfinder 2e Character Sheet for Roll20

An unofficial community conversion of the official Pathfinder Second Edition by Roll20
sheet, retooled for Starfinder 2e. It adds the **Computers (Int)** and **Piloting (Dex)**
skills and reskins the sheet in a Starfinder blue / cyan / light-purple color theme. The
Starfinder logo is already built in, so there is nothing you need to host or configure.

Because Starfinder 2e shares the same core rules as Pathfinder 2e, everything else on the
sheet (saves, AC, strikes, spells, proficiency math, and all the automation) works exactly
as it does on the original Pathfinder sheet. The two new skills auto-calculate just like the
built-in ones and have their own roll buttons, notes fields, and settings.

---

## What's in the download

- `starfinder2.html` — the sheet layout
- `starfinder2.css` — the colors and styling
- `_translation.json` — the text labels (this one matters, see the warning below)

That's all three files you need. Grab them and save them somewhere you can find them.

---

## Setup (about 3 minutes)

You do NOT need a text editor or any coding. You're just copying and pasting.

**You need a Roll20 Pro subscription** to use custom sheets.

### Step 1 — Open your game's sheet settings

1. In Roll20, open the game you want to use the sheet in.
2. Go to the **gear icon (Settings) > Game Settings**.
3. Scroll down to **Character Sheet Template** and pick **Custom** from the dropdown.
4. Four tabs appear: **HTML**, **CSS**, **Translation**, and a Preview.

### Step 2 — Paste in the three files

Open each file (Notepad on Windows, or TextEdit on Mac), select all (Ctrl+A / Cmd+A),
copy (Ctrl+C / Cmd+C), and paste it into the matching tab:

1. `starfinder2.html`  →  **HTML** tab
2. `starfinder2.css`  →  **CSS** tab
3. `_translation.json`  →  **Translation** tab

> **Do not skip the Translation tab.** This is the single most common mistake. If the
> Translation tab is empty, the sheet still loads, but every label shows up as red text in
> brackets with underscores, like `[CHARACTER_SHEET]` and `[ANCESTRY_HERITAGE]`. That red
> bracketed text is Roll20 telling you the translation is missing. Paste `_translation.json`
> into the Translation tab and the labels turn into normal readable words.

### Step 3 — Turn off Legacy Sanitization

On the same settings page, find the **Legacy Sanitization** checkbox and make sure it is
**unchecked**. This sheet uses sheet worker scripts for the skill calculations, and they
behave best with it off.

### Step 4 — Save

Click **Save Changes** at the bottom of the settings page.

### Step 5 — Open a character to see it

1. Launch or reopen your game.
2. Open the **Journal** panel on the right, click **+ Add**, and choose **Character**.
3. Open that character. The sheet appears in Starfinder colors with all labels readable.

---

## Troubleshooting

**All the labels are red text in brackets with underscores (like `[CLASS]`).**
The Translation tab is empty or wasn't saved. Redo Step 2 for `_translation.json`, make sure
it lands in the **Translation** tab specifically, and click Save Changes.

**The Preview tab looks like one broken vertical column.**
Ignore it. Roll20's built-in preview is unreliable and doesn't apply the translation file, so
it always looks wrong. The real sheet only renders correctly on an actual character (Step 5).

**The logo doesn't show up.**
Refresh the page. If it still doesn't appear, the image host may be temporarily down; the
sheet still works fine without it.

**Computers and Piloting aren't calculating.**
Confirm Legacy Sanitization is unchecked (Step 3), then save and reopen the character. These
two skills run on the same sheet worker scripts as every other skill.

---

## About Lore

Lore works exactly as it does on the Pathfinder 2e sheet: it's the add-your-own repeating
section below the main skill list, so you can add "Lore: Astronomy," "Lore: Starships," and
so on. It was intentionally left unchanged.

---

## Legal

Starfinder, Pathfinder, the Paizo golem logo, and associated names and likenesses are
trademarks and/or copyright of Paizo Inc. This is an unofficial, fan-made sheet and is not
published, endorsed, or affiliated with Paizo Inc. It is provided free for personal use.
This conversion is based on the "Pathfinder Second Edition by Roll20" community sheet.
