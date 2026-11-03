### Adam Acovski

Hydrogeologist and data engineer in Denver. I build calibrated groundwater models with
honest uncertainty, and the pipelines, APIs and dashboards that put their results in
front of the people making decisions.

[Portfolio & résumé](https://adacovsk.github.io) · [LinkedIn](https://www.linkedin.com/in/adam-acovski-3625521a6) · [Work GitHub](https://github.com/aacovski) · adacovsk@gmail.com

**Day job** — mine-site groundwater models in MODFLOW 6 / FloPy, calibrated with PEST++
iterative ensemble smoothers; monitoring data in DuckDB / DuckLake, served through
FastAPI and React.

**Toolbox**

| | |
|---|---|
| Modeling | MODFLOW 6, FloPy, FEFLOW, MINEDW, PEST/PEST++ (IES), Leapfrog |
| Data | Python (pandas, NumPy, SciPy), SQL, PostgreSQL, DuckDB, DuckLake, FastAPI |
| Infra | GCP (Cloud Run, Cloud SQL, Compute Engine), AWS, Pulumi, Docker, GitHub Actions |
| Also | Rust (Bevy), C++, React, Three.js, Plotly |

**bevy-rpg** *(private)* — my main side project: an isometric tactical CRPG in Rust/Bevy
built on the ORC-licensed d20 ruleset. ~450k lines of Rust, ~9,300 tests, 18k+ commits
since July 2025.

- **Rules engine** — 130+ ECS systems covering characters, ancestries, classes, feats,
  spells, conditions, degree-of-success combat, encumbrance, stealth, summoning, rest and
  earning income.
- **Living world** — procedural terrain (Voronoi + Perlin), biomes, settlements, dungeons
  and roads; caravans with their own economics, NPC routines and AI, generated quests and
  random encounters.
- **Data-driven content** — ~300 JSON content files with generated schemas, 40+ validation
  guards and hot reload; nothing content-specific is hardcoded in Rust.
- **Pipeline** — deterministic asset builds (sprites, atlases, Tiled maps), GPU particle VFX
  with bevy_hanabi, performance budgets checked against Chrome traces, coverage reports.
- **Agent-run development** — I orchestrate a team of AI agents (architect, planner,
  coordinator, tester) through [Paperclip](https://github.com/adacovsk/paperclip); changes
  land through a local verification gate, with a cost-budgeted CI behind it.

**Other projects**

- [**typefossil**](https://github.com/adacovsk/typefossil) — recovers a working digital typeface from photographs of a printed book by averaging hundreds of impressions of each sort.
- [**python-experiments**](https://github.com/adacovsk/python-experiments) — ML odds and ends: Real-ESRGAN video upscaling, FLUX-painted game icons and portraits.
