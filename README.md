# Probably Stolen — 1.0 Cheatsheet

A source-linked reference for **Probably Stolen** (Questing Goose Studio / tinyBuild).
Every entry is checked against official announcements, patch notes or SteamDB; anything
the developer has not published is marked **Not published** instead of guessed.

> Unofficial fan project. Not affiliated with Questing Goose Studio or tinyBuild.
> Verified 28 October 2026 against the 1.0 release.

## Contents

- [Starting professions](#starting-professions-10)
- [Production chains](#production-chains)
- [Endings and security](#endings-and-security)
- [Save file and troubleshooting](#save-file-and-troubleshooting)
- [Sources](#sources)

## Starting professions (1.0)

| Profession | 中文名 | Starting setup | Playstyle / risk |
| --- | --- | --- | --- |
| Apprentice | 学徒 | Starts from nothing, learns the loop while upgrading | Generalist; most beginner-friendly |
| Water Merchant | 水商 | Water testing and purification kit | Fast early cash; relabelling carries risk |
| Fence | 销赃人 | Stolen goods | High turnover; frequent searches |
| Rock Bottom | 一贫如洗 | Starts with nothing | Official highest-difficulty challenge |
| Hydroponic Farmer | 水培农场主 | Hydroponic machines and farm supplies | Cyclical output; late-game GMO contraband |
| Gunsmith | 枪械匠 | Class 1 weapon permit, guns, ammo | High profit; frequent security inspections |
| Chemist | 化学家 | Chemistry lab equipment | Secret recipes; depends on purification |
| Rat Wrangler | 养鼠人 | Mutant rat breeding | High maintenance; official 2×3 giant rat challenge |
| Aquafarmer | 水产养殖户 | Recirculating system, Tilapia fry, feed | Slower, lower maintenance; eels and sturgeon later |

Starting money: **Not published** — varies with the four difficulty levels.
Organ Trader, Junker and Street Food Vendor are confirmed for post-launch.

Raw data: [`data/professions.csv`](data/professions.csv)

## Production chains

- **Aquaculture** — unlock via Wild's network, then buy tanks from the retired
  aquaculturist. Tilapia → eels / sturgeon. Keep water quality, filters and the
  energy battery running; adults lay eggs that hatch into fry. Knife for meat and
  special resources; surgical tools on a sturgeon for caviar.
- **Water** — Aquascan reads purity; filters plus the Hydratech Micro Purifier
  reach 98%+; the UV-Filter only works on items you own.
- **Bottle Printer** — electronic components unlock standard and large bottle printing.
- **Vacuum Robot** — one Common Electronic unlocks incineration (2× power, burns
  collected rat droppings and trash).
- **Toolbox** — after day 14 from Dr. Jackson; bind tools to number keys 1–9.
- **Vending machines** — stock them to sell overnight while the shop is closed.

Full chemistry recipe list, quantities and margins: **Not published**.

Raw data: [`data/production-chains.csv`](data/production-chains.csv)

## Endings and security

- **Win condition** — buy the shop from the landlord before the rising weekly rent
  buries you. Required amount: **Not published**.
- **Endgame stats** — most profitable sale, days survived, total worth, perks unlocked.
- **Sentinel Collapse Disorder** — do not take it on a first run; the 1.0 announcement
  warns it can kill a save.
- **Security officer** — arrives the morning after an investigation ends. Fine vs.
  arrest is decided when the officer reaches the shop, based on the evidence value at
  that moment. Clear it with a fixer (Wild) the night before, or let it decay.
  Thresholds and fine amounts: **Not published**.

Raw data: [`data/endings-security.csv`](data/endings-security.csv)

## Save file and troubleshooting

Windows save directory:

```text
%USERPROFILE%\AppData\LocalLow\Questing Goose Studio\Probably Stolen
```

- Saves are `.es3` files (Unity Easy Save 3) and support Steam Cloud.
- Demo saves load in 1.0, but the developer recommends starting a new game.
- A long black screen during sleep is the save being written. Do not Alt+F4.
- The demo is delisted at launch, and demo-era mods do not work in 1.0.

Raw data: [`data/save-file.csv`](data/save-file.csv)

## Sources

- Full bilingual guides: [English](https://navgame.org/en/games/probably-stolen) ·
  [中文](https://navgame.org/zh/games/probably-stolen)
- [All 9 starting professions](https://navgame.org/en/games/probably-stolen/starting-professions) ·
  [9 个开局身份全解析](https://navgame.org/zh/games/probably-stolen/starting-professions)
- [Production chains and machine upgrades](https://navgame.org/en/games/probably-stolen/production-chains) ·
  [生产链与机器升级](https://navgame.org/zh/games/probably-stolen/production-chains)
- [Endings and security arrests](https://navgame.org/en/games/probably-stolen/endings-and-security) ·
  [结局条件与治安逮捕判定](https://navgame.org/zh/games/probably-stolen/endings-and-security)
- [Save file, demo transfer and black screen fixes](https://navgame.org/en/games/probably-stolen/save-file-demo-crash-fixes) ·
  [存档位置、Demo 继承与黑屏排查](https://navgame.org/zh/games/probably-stolen/save-file-demo-crash-fixes)

## Contributing

Corrections with an official source are welcome. Open an issue with the source link
and what should change.

## License

MIT for the repository text and data files. Game names, screenshots and trademarks
belong to their respective owners.
