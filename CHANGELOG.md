# v0.3.0

- Added ATDART % Target above Legacy Dungeons: lowest completion fraction across legacy raids/dungeons, with random tie selection once per captured snapshot. Targets persist across browsing and reloads.
- ATT captures now retain total/progress, including complete instances for the target. Existing opportunity lists continue to use missing counts and show unfinished content only. Older snapshots ask for a refresh rather than inventing percentages.
- Added Census → Profession blindspots, covering all 156 standard expansion profession skills from Classic through Midnight. Profession/expansion filters, gap/all views, owner counts, best ranks, paging, and roster shortcuts are included.
- Coverage distinguishes recorded owners, unscanned base-profession owners, and no owner recorded. It flags characters missing profession snapshots and does not claim definitive account-wide absence.
- Added direct gathering/expansion rank capture where supported by Blizzard APIs and zero-rank scan checks. Preserved recipe/knowledge details when refreshing expansion ranks.
- Extended Lua 5.1 regression checks for percentages, ties, persistence, old snapshots, coverage states, localization, gathering, navigation, and frame reuse.

# v0.2.1

- Raised header buttons above the draggable header so X receives clicks.
- Swapped ATT and Reputations tabs.
- Reworked trans pride into pastel pink/light blue surfaces and light mode into bright blue/pink/lavender colors with dark text.
- Resolved outdoor zone expansions from ATT source ancestry and Blizzard map ancestry, including distinct Outland/Draenor and Midnight versions of zones.
- Legacy dungeon/raid lists now stop at Dragonflight. The War Within, Midnight, and unclassified instances are excluded, including from older saved snapshots.
- Added regression checks for closing, control layering, tab order, bright theme text contrast, headerless zone groups, legacy cutoff, and cached snapshot display.

# v0.2.0

- Tightened stat cards, profession rows, census spacing, and settings paragraphs; removed the background footer line.
- Added eight themes and a background opacity slider that leaves text fully opaque.
- Added common/custom tag picker with selection indicators and Save tags; tags appear beside identity information.
- Fixed notebook mouse/keyboard input, category switching, saved feedback, and explicit Save note.
- Fixed roster search focus, paging/realm controls, and resize anchoring with cursor delta tracking.
- Switched to Retail namespaced specialization APIs and added hero specialization summaries.
- Added movement percentage, speed rating, and speed bonus to character stats.
- Preserved existing snapshots when APIs return unavailable values; logout updates whereabouts without overwriting stats.
- Added automatic NA-US/OCE/LATAM/BR realm classification and migration.
- Excluded Archaeology; moved Cooking/Fishing below primary professions. Profession, specialization, and title headers collapse.
- Changed the highest census band to 90s and removed ATT color markup from displayed names/profile labels.
- Extended Lua 5.1 regression checks; actual Retail client validation remains required.

# 0.1.0

- First character-folio release with a purple fantasy dossier presentation.
- Collect identity, level/XP, spec/role, attributes, item level, rested XP, guild, location, hearthstone, talents, titles, professions/expansion skills, reputation/renown, and account collection milestone snapshots.
- Add searchable/paginated warband roster, realm collapse controls, combined filters, exact XP sorting, and role-capability prioritization.
- Add persistent per-character notes and tags.
- Add Warband Census and nearest-to-next-level list.
- Add optional read-only ATT adapter, active-profile opportunities, zone quest deduplication, capital exclusions, and missing/disabled/not-ready messages.
- Add minimap button, slash commands, resizable saved window, and Concentration Planner shortcut.
- Add Lua 5.1 behavior/UI tests with 400 simulated alts.
