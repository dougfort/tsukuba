# Supersession Cleanup Map — Tsukuba Project

*Second pass. Focuses on discrepancies, naming anomalies, files missing from the INDEX, and the confirmed duplicate.*

---

## 1. Confirmed Exact Duplicate — Delete One

| Keep | Delete | Status |
|------|--------|--------|
| `character_mori_hiroshi.md` | `character_mori_hiroshi__1_.md` | Files are byte-for-byte identical. The `__1_` version is a filesystem artifact (Obsidian or the upload process mangling `(1)` in the filename). **Delete `character_mori_hiroshi__1_.md` without any content review needed.** |

The INDEX correctly references `[[character_mori_hiroshi]]` only. The `__1_` file is not linked from anywhere.

---

## 2. Files Present in Project But Missing from INDEX

These files exist in the project folder but are **not listed in INDEX.md**. Each needs to be either added to the INDEX or confirmed as intentionally unlisted (e.g., working documents).

| File | Contents (brief) | Suggested INDEX section |
|------|-----------------|------------------------|
| `character_psychological_profiles.md` | Deep psychological profiles of all three boys — goes significantly beyond the character sheets | **Characters → The Boys**, or a new **Profiles** subsection |
| `nushi_contact_history.md` | Chronological history of Nushi's contact with the boys | **The Alien Intelligence** |
| `nushi_distributed_intelligence_research.md` | Research survey — fiction, science, and what is/isn't useful for Nushi | **The Alien Intelligence** or a new **Research Notes** section |
| `nushi_perception.md` | How Nushi perceives — senses, cognition, experience of time | **The Alien Intelligence** |
| `shin_notebook.md` | Shin's notebook — concept and anticipated entries | **Characters → The Boys** or **World and Setting** |
| `narrative_prologue.md` | Drafted narrative prologue | New **Narrative Drafts** section |
| `narrative_channel_discovery.md` | Drafted narrative scene — channel discovery | New **Narrative Drafts** section |
| `story_structure.md` | Story structure and arc notes | New **Story Structure** section |
| `world_drainage_channel.md` | The drainage channel as physical and narrative space | **World and Setting** |
| `world_drainage_channel_sacred_history.md` | The channel's sacred and historical layering | **World and Setting** |
| `world_school.md` | The boys' school — setting and social world | **World and Setting** |
| `world_what_the_boys_play.md` | Play culture, games, menko, the mountain card | **World and Setting** |

---

## 3. Files Referenced in INDEX That Do Not Exist

The INDEX links to two files that are **not present** in the project folder:

| INDEX link | Status | Notes |
|------------|--------|-------|
| `[[mount_tsukuba_manyoshu]]` | **File does not exist** | Referenced under World and Setting as "Mount Tsukuba in the Man'yoshu — folkloric and poetic background." Also flagged in `todo.md` as research still to do. The content likely belongs in `world_drainage_channel_sacred_history.md` or needs its own file. |
| `[[distributed_intelligence]]` | **File does not exist** | Referenced under The Alien Intelligence as "Nushi's nature — nodes, Boltzmann Brain, deep history." This content may have been developed into `nushi_distributed_intelligence_research.md` and/or `nushi_perception.md`. Needs verification and either a redirect note or INDEX correction. |

---

## 4. INDEX Description Mismatches

Some INDEX descriptions no longer fully reflect the scope of the files they point to.

| File | INDEX says | Actual scope | Suggested fix |
|------|-----------|--------------|---------------|
| `nushi_first_awareness.md` | "Nushi's discovery of the boys — from annoyance to intention" | File covers this but is substantially longer and richer than the description implies | Update INDEX description |
| `nushi.md` | "Nushi 主 — the name, folkloric meaning, significance" | Also covers adult reactions and thematic significance in depth | Update INDEX description |
| `mittsu_no_hoshi.md` | "The boys as a group — dynamic, territory, the name" | Also covers their developing abilities and open questions about the group dynamic | Minor update to INDEX description |

---

## 5. Summary of Actions Needed

**Immediate (no content decisions required):**
- [ ] Delete `character_mori_hiroshi__1_.md` — exact duplicate
- [ ] Add all 12 missing files to INDEX.md with accurate descriptions

**Requires content decision:**
- [ ] Decide whether `[[distributed_intelligence]]` was superseded by `nushi_distributed_intelligence_research.md` and/or `nushi_perception.md` — if so, correct the INDEX link
- [ ] Decide whether `[[mount_tsukuba_manyoshu]]` content lives in `world_drainage_channel_sacred_history.md` or needs a dedicated file — correct or create accordingly

**Optional cleanup:**
- [ ] Update INDEX descriptions for `nushi_first_awareness.md`, `nushi.md`, and `mittsu_no_hoshi.md` to reflect actual scope
