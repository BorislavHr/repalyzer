# Third-party notices

Repalyzer includes the following third-party software. Each component stays under its own licence. The licence texts are in [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

| Component | Author | Licence | What Repalyzer uses it for |
|---|---|---|---|
| [screp](https://github.com/icza/screp) 1.13.3 (unmodified binary) | András Belicza (icza) | Apache-2.0 | Parsing StarCraft replay files |
| [OpenBW](https://github.com/OpenBW/openbw), via [Alex Pineda's fork](https://github.com/alexpineda/openbw) (commit `86fc7f6d`) with Repalyzer's own fixes | OpenBW contributors; Alex Pineda | - | Simulating games to measure economy, supply and timings |
| [casc](https://github.com/jybp/casc) (`cmd/casc` binary) | jybp | - | Reading game data from the user's own StarCraft installation |
| [downgrade-replay](https://github.com/alexpineda/downgrade-replay) (vendored, with local changes) | Alex Pineda | MIT | Converting SC:R replays to the layout the engine reads |
| [pkware-wasm](https://github.com/imbateam-gg/pkware-wasm) 1.0.0 | Alex Pineda | MIT | PKWARE compression used by replay files |
| [@shieldbattery/broodrep](https://github.com/ShieldBattery/broodrep) 0.5.0 | ShieldBattery | MIT or Apache-2.0 (used under MIT) | Reading replay metadata |
| [bl](https://github.com/rvagg/bl) 5.1.0 | bl contributors | MIT | Buffer handling |
| [iconv-lite](https://github.com/ashtuchkin/iconv-lite) 0.6.3 | Alexander Shtuchkin | MIT | Text encoding conversion |
| [Electron](https://www.electronjs.org/) and Chromium | OpenJS Foundation, Chromium authors | MIT and various | The application shell (licence files are in the installation folder) |
| [Inter](https://github.com/rsms/inter) typeface | The Inter Project Authors | SIL OFL 1.1 | App font |

Repalyzer's own helper programs are by Grast: the screp supervisor (a process-containment wrapper around screp) and the hidden-unit analysis program, which is built on the OpenBW engine listed above.

StarCraft and Brood War are trademarks of Blizzard Entertainment, Inc. Repalyzer is not affiliated with Blizzard and contains no game data.

<!-- Before publishing: fill in the two TO CONFIRM licence cells once the OpenBW and casc authors have replied (see permission-requests.md), then delete this comment. -->
