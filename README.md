# <img src="res/logo.png" width=100> Bible-Reading Scheduler Application
###### *Gentle and constant.*

**A single-file web application for generating customized Bible-reading schedules with progress tracking and print-friendly output. Works entirely offline in any modern browser — no server required.**

<details>
<summary>Preview…</summary><br/>

<img src="res/BRiSA.gif" width=800>

</details><br/>

<details>
<summary>Features…</summary><br/>

### Reading Plans

- **Orderings**: Choose from Canonical (Bible order), Chronological (historical order)[^1], Completion (by date of completion), or Thematic (grouped by type of composition).
- **Thematic groups**: Predefined book collections including Pentateuch, Historical Books, Gospels and Acts, Poetic Writings, Major and Minor Prophets, Revelation, Paul's Letters, and Other Letters, with combined options.
- **Categories**: Filter by verse type including History, Verse/Poetry, Counsel/Advice, Prophecy, Law, Building/Construction and Genealogy[^1].
- **Duration**: Available durations adapt to the size of the selected content, ranging from 1 month to 48 months.

### Display Options

- **Language**: Select the language for scripture references.
- **Book name format**: Full names, standard abbreviations, or official abbreviations. Optional ALL CAPS toggle.
- **Scripture indent**: None, padding, or bullet markers for scripture references in the generated plan.
- **Layout**: Outline view or table views with 3, 5, 7 (one week), or 10 day columns.
- **Start date**: Set a commencement date for the plan. Day labels show dates instead of day numbers when set.
- **Links**: Choose between *WOL* (*Watchtower Online Library*)[^2] links or *JW Library*[^3] deep links. Scripture references become clickable links.
- **Preview**: Shows a preview of the generated plan. Checkbox status *is not retained* in the preview.

### Pop-out

- Opens the generated plan as a standalone HTML document.
- Checkboxes for tracking daily reading progress.
- Save button downloads the plan with progress embedded, allowing the user to replace their previous copy.
- Clear button resets all checkbox progress.
- Auto-scrolls to the last checked day when reopened.
- Print-friendly: checkboxes and links render cleanly when printed.

### Exports

- **HTML**: Standalone plan document with the current theme, language, and layout settings.
- **Markdown**: Plan with checkbox list format, including clickable links for each scripture reference.
- **CSV**: Spreadsheet-compatible format with the selected layout.
- **JSON**: Minimal format containing day number, label, and scripture references.

### Multi-language Support

Available languages include ASL (English text with sign language links), English, Español, Français, Português, Русский, and українська. The UI language controls the application interface, while the display language controls book names and plan content.

### Themes

Thirteen built-in themes.

### Configuration Sharing

The current configuration is encoded into the URL query parameter. Bookmark the page or copy the URL to save and share a specific plan setup. Opening the URL restores all settings including language, theme, ordering, and duration.

</details><br/>

**Download**: [BRiSA.html](https://github.com/erykjj/BRiSA/releases/latest/download/BRiSA.html)

**Launch directly**: [BRiSA](https://erykjj.github.io/BRiSA/BRiSA.html) *(use `Ctrl+Click` or middle-click for a new tab)*

____
### Feedback, etc.

Feel free to get in touch and post any [issues and/or suggestions](https://github.com/erykjj/BRiSA/issues).

[![Static Badge](https://img.shields.io/badge/releases-orange?style=plastic&logo=rss&logoColor=orange&color=black)](https://github.com/erykjj/BRiSA/releases.atom)

____
#### Footnotes:
[^1]: Chronologial ordering and category assignments will be fine-tuned over time.

[^2]: [*Watchtower Online Library*](https://wol.jw.org/) is a registered trademark of *Watch Tower Bible and Tract Society of Pennsylvania*.

[^3]: [*JW Library*](https://www.jw.org/en/online-help/jw-library/) is a registered trademark of *Watch Tower Bible and Tract Society of Pennsylvania*.