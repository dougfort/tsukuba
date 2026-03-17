# Tsukuba — Supersession Map

A record of which outputs files replace which project files, and what is new. Use this when syncing the outputs directory to the Claude project.

Last updated: 2026-03-11

---

## Status Key

- **REPLACE** — a current version exists in outputs; replace the project file with it
- **ADD** — new file not yet in the project; add it
- **KEEP** — project file is current; no action needed
- **DELETE** — file should be removed (duplicate or superseded artifact)
- **TOOL** — utility script, not a project document

---

## Action Required

### Files to Replace in Project

| Outputs file | Project file | Notes |
|---|---|---|
| `nushi_first_awareness.md` | `nushi_first_awareness.md` | **REPLACE** — revised to ambient awareness model; removes "forty-year silence" framing |
| `INDEX.md` | `INDEX.md` | **REPLACE** — fully revised; reflects current file taxonomy and all new documents |

### Files to Add to Project

| Outputs file | Category | Contents |
|---|---|---|
| `story_structure.md` | Planning | Prologue/epilogue frame, three-part structure, narrative streams, the notebook as parallel document |
| `timeline.md` | Planning | Full sequenced timeline from families' arrival through winter 1979-80 |
| `todo.md` | Planning | Running open questions and decisions |
| `character_psychological_profiles.md` | Character | Deep psychological profiles of all three boys; gestalt analysis of the trio |
| `world_drainage_channel.md` | World | Full physical description — section by section, ecology, seasonal character |
| `world_drainage_channel_sacred_history.md` | World | Channel's sacred history — iwakura, misogi spring, kagai approach route, kannagi use |
| `world_school.md` | World | The boys' school — building, routine, han system, each boy at school, the field trip |
| `world_shin_books_libraries.md` | World | Shin's book sources — school library, home library, University library, Watanabe-san |
| `world_what_the_boys_play.md` | World | Menko, beetle collecting, the mountain card as contact focus |
| `nushi_perception.md` | Nushi | Nushi's umwelt — sensory channels, memory systems, the channel before the boys |
| `nushi_contact_history.md` | Nushi | Contact history — kagai, kotodama, kannagi lineage, Meiji rupture, what Nushi knows by 1979 |
| `nushi_contact_mechanics.md` | Nushi | How Nushi reaches toward the boys — all contact channels, each boy's experience |
| `nushi_distributed_intelligence_research.md` | Nushi | Research survey — distributed intelligence in fiction and science |
| `shin_notebook.md` | Parallel | Shin's notebook — parallel document; first entry only (August 3, channel discovery) |
| `narrative_prologue.md` | Narrative | Prologue — Nushi's perspective, the Slope Node incident (first draft) |
| `narrative_channel_discovery.md` | Narrative | Chapter — boys' first discovery of the drainage channel (first draft) |

### Files to Delete from Project

| File | Location | Reason |
|---|---|---|
| `character_mori_hiroshi__1_.md` | Project | Exact duplicate of `character_mori_hiroshi.md` |

---

## Project Files Requiring No Action

These project files are current and have not been superseded.

| File | Notes |
|---|---|
| `character_kenji.md` | Current |
| `character_shin.md` | Current |
| `character_taro.md` | Current |
| `character_mori_hiroshi.md` | Current (keep this one; delete the `__1_` duplicate) |
| `character_mori_akiko.md` | Current |
| `character_nakamura_takashi.md` | Current |
| `character_nakamura_yuriko.md` | Current |
| `mittsu_no_hoshi.md` | Current |
| `nushi.md` | Current |

---

## Outputs Files to Discard

These outputs files have been superseded by renamed versions (under the agreed taxonomy) or are artifacts from earlier sessions. Once the renamed versions are safely imported to the project, these can be deleted from outputs.

| File | Superseded by |
|---|---|
| `drainage_channel.md` | `world_drainage_channel.md` |
| `drainage_channel_sacred_history.md` | `world_drainage_channel_sacred_history.md` |
| `the_school.md` | `world_school.md` |
| `shin_books_and_libraries.md` | `world_shin_books_libraries.md` |
| `what_the_boys_play.md` | `world_what_the_boys_play.md` |
| `distributed_intelligence_research.md` | `nushi_distributed_intelligence_research.md` |
| `nushi_first_contact.md` | `nushi_contact_mechanics.md` |
| `psychological_profiles.md` | `character_psychological_profiles.md` |
| `opening_draft.md` | `narrative_prologue.md` |
| `chapter_channel_discovery.md` | `narrative_channel_discovery.md` |
| `nushi_perception.docx` | Artifact from earlier session — discard |

---

## Utility Files (Not Project Documents)

| File | Notes |
|---|---|
| `tsukuba_sync.py` | Watch script — copies new `.md` files from Downloads to project folder automatically |
| `story_supersession_map.md` | This document — meta, not a story file; import to project for reference or keep locally |

---

## Recommended Sync Order

1. Delete `character_mori_hiroshi__1_.md` from project
2. Replace `nushi_first_awareness.md` in project with outputs version
3. Replace `INDEX.md` in project with outputs version
4. Add all files in the **Files to Add** table above
5. Confirm Obsidian has picked up all changes
6. Delete superseded outputs files listed in **Outputs Files to Discard**
