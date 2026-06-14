# RogueTech Codex — Data

Pre-built SQLite database for [RogueTech Codex](https://github.com/adamrogers/RogueTech-Codex), generated from the [RogueTech](https://github.com/BattletechModders/RogueTech) mod.

## About

`roguetech.db` is produced by the RogueTech Codex ingestion pipeline, which walks the RogueTech mod JSON files and writes a structured SQLite database covering chassis, variants, loadouts, gear, weapons, and affinities.

This repository exists solely to host the database as a release asset so that the [RogueTech Codex CI build](https://github.com/adamrogers/RogueTech-Codex/actions) can download it without bundling a 3 GB mod checkout into the build workflow.

## Releases

Each release contains a single asset: `roguetech.db`.

The `roguetech-db` tag is updated in place whenever the RogueTech mod receives a significant update. It is not versioned independently — use the RogueTech Codex release version for that.

## Licence

The database is derived from [RogueTech](https://github.com/BattletechModders/RogueTech) mod data. Refer to that project for its licence terms.

The pipeline code that generates this database is part of RogueTech Codex and is licenced under [GPL v3](https://github.com/adamrogers/RogueTech-Codex/blob/main/LICENSE).
