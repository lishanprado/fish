# Fish Trainer

A browser-based simulator and strategy trainer for **Fish** (also called Literature). Play 2v2 or 3v3 against deduction-based bots with four difficulty levels.

## Features

- 2v2 and 3v3 games
- Novice, Intermediate, Advanced, and Expert bots
- Per-bot knowledge and public-information deductions
- Manual or automatic bot pacing
- Set declarations and spectator mode
- Downloadable full game reports and bot decision audits
- No installation, account, backend, or external dependencies

## Play locally

Open `index.html` in a modern browser.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload every file in this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then save.

Your site will be available at:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Project structure

```text
index.html            Complete game and interface
favicon.svg           Browser icon
manifest.webmanifest  Installable-site metadata
robots.txt            Search-crawler instructions
.nojekyll              Disables unnecessary Jekyll processing
```

## Development note

The simulator is intentionally self-contained. The HTML, CSS, and JavaScript are all in `index.html`, which makes deployment and sharing simple. The bot decision firewall is designed to limit strategy code to the bot's own hand, public hand counts, and public move history.
