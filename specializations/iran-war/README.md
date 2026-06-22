# Specialization: The 2026 Iran War

A schema-conformant specialization of the SuperGoodReasonModel applied to one System of Interest — the 2026 war between the United States and Israel and Iran. It is the first end-to-end-validated specialization of the canonical model.

**Snapshot:** 13 June 2026. Source-verified: 25 claims (21 confirmed, 4 partial, 0 refuted) across 24 sources (IAEA, ACLED, ISIS, UK Parliament). Casualty/damage figures are party claims. The structural layers age in weeks; current-state details in days.

## Files

| File | What it is | Conformance |
|---|---|---|
| `iran-war.supergoodreason-model.json` | Full template clone: metadata + 8×7 sectors (56 nodes × 8 perspectives = 448 cells) + circles | **Validates end-to-end against the schema** |
| `iran-war.supergoodreason-instance.json` | Application: adds SOI/MOI, 28 pairwise interactions, the worked `unify(S,J,C)→R` | circles + lineage schema-checked |

## Validate

```bash
uv run ../../tools/validate_supergoodreason.py iran-war.supergoodreason-model.json
uv run ../../tools/validate_supergoodreason.py iran-war.supergoodreason-instance.json
```

## Related applications (elsewhere)

- **3D visualization cube** — `goodreason-relationships-3d-visualization/cubes/iran-war/`, deployed at `https://softagram.com/materials/goodreason-iran-war/`. Its 1D Levels view renders these 56 nodes along the canonical per-sector ladders.
- **A3 poster, podcast script, narrative, and the verified research report** live in the originating holarchy `_input/` working area.
