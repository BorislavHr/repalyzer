# Repalyzer

**Your replays have more to teach you.**

Repalyzer is a free Windows app that turns your StarCraft: Remastered replays into a searchable library, player trends and an in-depth review of every game: APM, hotkeys, build orders, economy, a 0–10 Skill shape, and the one thing to fix before your next game. It works offline, needs no account, and never uploads your replays.

Made by **Grast** (Borislav Christov) for the Brood War community.

- **Website, screenshots, install guide and FAQ:** https://starkraftika.com/repalyzer
- **Support and feedback:** [Discord, the Repalyzer channel on the Team Psi server](https://discord.gg/AB6VKn7Mmk)

## Download

Get the latest installer from the **[Releases page](../../releases/latest)**: `Repalyzer-Setup-<version>.exe` (about 110 MB, Windows 10 or 11, 64-bit).

The same installer is also available from https://starkraftika.com/repalyzer/download.

### The installer is unsigned

Repalyzer is a free hobby project and the installer is not code-signed, so your browser and Windows SmartScreen will warn you ("Unknown publisher"). That is expected. To be sure you have the genuine file:

1. Download the installer and the `.sha256` file from the same release, or read the checksum in the release notes.
2. In a terminal in your Downloads folder, run:

   ```text
   certutil -hashfile Repalyzer-Setup-<version>.exe SHA256
   ```
3. The result must match the published SHA-256 exactly. If it does, choose **More info**, then **Run anyway** in SmartScreen.

The page https://starkraftika.com/repalyzer has the full step-by-step guide.

## What you need

- Windows 10 or 11 (64-bit). There is no Mac or Linux version.
- StarCraft: Remastered replays (older 1.16 replays work too).
- For the simulation-based tabs (income, workers and supply, Adept benchmarking, hidden-unit scan), StarCraft installed from Battle.net. The free version is enough and the game does not need to be running. Everything else works from the replay file alone.

## Privacy

Replays are read on your PC. Nothing is uploaded, and your original files are never changed, moved or deleted unless you ask.

## Credits and third-party software

Repalyzer stands on the work of other people in the Brood War and open-source community. Thank you to:

- **[screp](https://github.com/icza/screp)** by András Belicza (icza), the StarCraft replay parser Repalyzer uses to read replay files.
- **[OpenBW](https://github.com/OpenBW/openbw)**, the open-source Brood War engine that Repalyzer uses to simulate games, and **[Alex Pineda's fork](https://github.com/alexpineda/openbw)** it is built on.
- **[downgrade-replay](https://github.com/alexpineda/downgrade-replay)** and **[pkware-wasm](https://github.com/imbateam-gg/pkware-wasm)** by Alex Pineda, which convert SC:R replays so the engine can read them.
- **[broodrep](https://github.com/ShieldBattery/broodrep)** from the [ShieldBattery](https://shieldbattery.net) project.
- **[casc](https://github.com/jybp/casc)** by jybp, used to read game data from your own StarCraft installation.
- Electron, Chromium, the Inter typeface and the other libraries listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Full licence texts are in [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt) and are also installed with the app.

## Licence

Repalyzer is free to use and share. See [LICENSE](LICENSE) for the terms.

## Disclaimer

Repalyzer is an unofficial fan project and is not affiliated with, endorsed by or sponsored by Blizzard Entertainment. StarCraft and Brood War are trademarks or registered trademarks of Blizzard Entertainment, Inc. Repalyzer does not include any StarCraft game data; the simulation features read data from your own installation. The integrity review reports evidence only and never declares a player guilty.
