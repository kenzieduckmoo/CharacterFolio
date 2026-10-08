# Character Folio development

- Keep this addon separate from Concentration Planner. Folder: DuckMooFolio. SavedVariable: DuckMooFolioDB.
- Preserve per-character notes and tags when updating snapshots or introducing migrations.
- Target Lua 5.1 and WoW Retail. Never open professions through protected APIs or automate gameplay.
- Missing snapshots are unknown, not proof of missing progress. Offline information is timestamped.
- Role filters include capable classes and prioritize the last recorded role. XP sorting uses unrounded values.
- ATT integration is optional, read-only, batched, and labeled with its captured profile context.
- Do not copy ATT live tables/metatables into SavedVariables. Filter restricted values.
- Verify code with tests/run_tests.py, package with the same DuckMooFolio root folder, and report actual client checks separately.
- Canonical repository: https://github.com/kenzieduckmoo/CharacterFolio. Future changes belong here, separate from Concentration Planner and FiasATDART.
- Keep the install folder DuckMooFolio and SavedVariable DuckMooFolioDB unchanged. From the repository root run python3 tests/run_tests.py and python3 tools/package.py. Package output in dist must exclude repository metadata and generated archives.
