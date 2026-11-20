# Adjutant

A Windows companion for Hearts of Iron IV. Pick a country and get a numbered route through its focus tree, with the decisions, advisors, laws and builds that go with it. Follow your own save and Adjutant keeps up as you play. Or choose a role and get a complete equipment design and division template, built from your installed game files.

[Download the Windows installer](https://github.com/plataodomo/Adjutant/releases/latest)

## Get started

1. Download `Adjutant-Setup-<version>.exe` from Releases.
2. Run Setup and choose whether to create a desktop shortcut.
3. Open Adjutant from the Start menu or your desktop shortcut. Python is included.
4. Choose a country guide, follow your game, or pick a quick build.

Requires Windows x64 and a local Steam installation of HOI4. Adjutant plans for the base game; mods are not supported. All DLC are assumed. Checked against HOI4 1.20.0.

## Features

### Country guides
- Numbered focus routes for 57 countries, with the research, decisions and events each step waits on.
- Government: which laws to pass, which advisors to hire, and which ones your path will dismiss.
- Doctrines, occupation laws, spy agency plans, and Army, Navy and Air Force builds for the route.
- Guides are checked against your installed HOI4, so a game update that changes a tree is flagged.

### Follow your game
- Adjutant reads your newest save after each autosave, in single player and multiplayer.
- While you play, it shows HOI4's date and hour live, and your focus and spy operations count their days on between autosaves.
- Completed focuses, decisions and missions are ticked off; focuses your campaign can no longer take drop out.
- When a focus is blocked, it tells you why and what to click.
- When a focus finishes, a Windows notification names the next one on your path. Turn on **Pick it for me in HOI4** and Adjutant starts that focus itself with HOI4's own keys (HOI4 in English).

### Designer
- Complete land, air and naval equipment builds, with matching divisions where applicable.
- Economy, Balanced and Elite priorities, with enemy and terrain choices.
- Doctrine paths, earned mastery and division slot limits.
- Production estimates, build comparisons and game artwork from your own installation.

Design statistics are planning estimates. No template is best in every situation.

## Updates

Adjutant 0.9.0 and later check this repository for releases and download updates in the background. Open **Updates > Restart to update** when ready. Automatic checks and downloads can be turned off in Updates. The Adjutant-Portable ZIP on each release is the file the updater downloads; install Adjutant with the setup.

Older versions need a one-time manual installation of the latest version. Campaign snapshots stay in Saved Games/Adjutant/data. Game updates are detected separately while the app runs.

## Tips

- Turn on **Daily** autosave in HOI4's settings so Adjutant can follow your game closely.
- If you play with Steam Cloud saves, large late-game autosaves can be cut short by Steam. Use **Campaign > Save autosaves to Documents** while HOI4 is closed.

## Privacy

Adjutant works locally without an account. Updates use GitHub; The Dispatch loads official HOI4 news from Steam when opened. Game files and saves are read on your computer and are never uploaded or changed. While it follows a game, Adjutant reads HOI4's date from the game's memory: it only reads, keeps nothing but the date, and can be turned off under **Campaign > Live game date**. With **Pick it for me in HOI4** turned on, Adjutant also presses HOI4's own keys to start your next focus, and looks at HOI4's top bar and focus screen while it does; it keeps no pictures and never writes to the game's memory or files. No game artwork is bundled.

Built by plataodomo. Copyright (c) 2026 plataodomo.
