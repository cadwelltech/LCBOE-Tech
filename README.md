# LCS Tech Hub

Tech help website for Laurens County Schools teachers.

## How to update the site

1. Open `index.html` in any text editor (VS Code, Notepad, TextEdit).
2. Edit the `SITE_DATA` section near the top — instructions are in the file. That's where all updates, projects, videos, and links live. Never touch anything below the "STOP EDITING" line.
3. Save the file.
4. Open **GitHub Desktop** — it will show your change.
5. Type a short summary (e.g., "Added October copier update"), click **Commit to main**, then click **Push origin**.
6. The live site updates automatically in about a minute.

## Common edits

- **New update card:** copy an existing `{ ... },` block in `updates`, paste it at the TOP of the list, edit the text.
- **NEW badge:** set `isNew: true` (change to `false` when it's old news).
- **Add a video:** paste a YouTube embed URL (Share → Embed → copy the `src` URL) into `embedUrl`.
- **Webticket link:** set `ticketUrl` to your ticket system's URL.
